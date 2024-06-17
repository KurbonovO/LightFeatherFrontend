### Prerequisites

 - run: npm install
 - run: npm run build

### To run

 - run: npm run start
 - go to url: localhost:3000

### docker
#### Run this to build: docker build --tag=lightfeatherfrontend-react-template:latest .

#### Run a container: docker run -d --name lightfeatherfrontend-react-template -p3000:3000 lightfeatherfrontend-react-template:latest

#### When you are done testing, stop the server and remove the container: docker rm -f lightfeatherfrontend-react-template