# Student_Rest_API_Newman

## How to run this project
- Clone this project
- Open with Postman / Command Shell
- Run Command:  
```console 
newman run StudentDetails.postman_collection.json -e StudentDetails.postman_environment.json 
```
- Run Command for Report: 
```console 
newman run StudentDetails.postman_collection.json -e StudentDetails.postman_environment.json -r cli,htmlextra
```

## Technology used:
- Postman
- Newman

## Prerequisite:
- Jdk
- Node Js
- Newman
- Html Report Library

## Newman and Report Installation Process:
- Newman Install Command:
```console
npm install -g newman-reporter-htmlextra
```
- Newman Html Report Install Command:
```console
npm install -g newman-reporter-htmlextra
```

## API Documentation:
- https://documenter.getpostman.com/view/13082503/2s93Xwz4Az

## Newman Report Summary:
![Newman Report Summary](https://user-images.githubusercontent.com/70250199/232209683-ddb8e3c5-4f23-4355-8919-61cd6ddca91a.png)

![Newman Report Summary](https://user-images.githubusercontent.com/70250199/232209794-f84c539b-e3cf-4e80-ab0e-9d6d59b1a339.png)
