To run the container:

1. build the docker image

   ```sh
   docker build -t photos .

   ```

2. you must expose port 80 because of NGINX

     ```sh
   docker run -d -p 8080:80 photos

   ```

3. in your browser, acess

     ```sh
   localhost:8080

   ```     
