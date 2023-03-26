### Building and Running the App using Docker
```
docker build -t shevchyk/node-app .
docker run -cpus=.5 -m 512m -p 80:3000 shevchyk/node-app
```
