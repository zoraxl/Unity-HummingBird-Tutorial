## Production-Grade Workflow

### Create React App Generator

To create a frontend react app: 
`npx create-react-app frontend` 

To build a docker with specific file: 
`docker build -f Dockerfile.dev .`

To run the docker just built: 
`docker run -it -p 3000:3000 <docker_id>`

Setting up the Docker Volume:
`docker run -it -p 3000:3000 -v /app/node_modules -v $(pwd):/app <docker_id>`


 