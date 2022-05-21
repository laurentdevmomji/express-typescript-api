# express-typescript-api
Express TypeScript API

## Build from source

1. Clone the repo

   ```sh
   git clone https://github.com/laurentdevmomji/express-typescript-api.git
   cd express-typescript-api
   ```

2. Install dependencies.

   ```sh
   npm install
   ```

3. Build the production server.

   ```sh
   npm build
   ```

4. Run the server.
   ```sh
   npm start
   ```

## Run NodeJS server + db (dev)

1. Run Docker Db
```sh
   docker-compose up
   ```

1. Run NodeJS server
```sh
   npm run dev
   ```
3. Go to :
    
    ```sh
    [http://localhost:8000/ping]
    ```
## Build Docker image locally

```sh
docker build -t express-typescript .
```

## Run tests

```sh
npm test
```