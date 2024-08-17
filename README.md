# eccom

an E-commerce Website built with MERN stack.

## Instructions

after cloning, run this command in the root folder
```bash
npm install
```
navigate to "frontend" folder, run these commands 
```bash
npm install
npm run build
```
wait for application build
after that open the backend/config/config.env
and update the MongoDB connection string
```bash
...
DB_LOCAL_URI=mongodb://localhost:27017/ecomm
```

navigate back to "root" folder and run this command for loading demo data
```bash
npm run seeder
```

run this below command to run the app in production mode
```bash
npm run prod
```


## Test
open the http://localhost:8000 and test the 

## Postman Collection
(https://web.postman.co/workspace/nodejsapi~61d4ae7f-f611-40d0-98b5-772d16179759/collection/37697083-029b52fa-673a-4ad7-ba53-88793b120d7f?action=share&source=copy-link&creator=37697083&active-environment=0fc3f74f-7990-4da6-b679-37c1cee0036f)


