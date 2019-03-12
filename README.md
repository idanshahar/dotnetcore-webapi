docker dotnet core webapi example app
=====================================


1. Clone the repo and cd to the directory
2. Build the image
```
docker build -t dotnetcore-webapi .
```
3. Run the image
```
docker run -d -p 8080:80 dotnetcore-webapi:latest
```
4. Browse to http://localhost:8080/api/values




