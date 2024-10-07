# Dockerized React

```sh
npx create-react-app dockerized-react
```

Inside that directory, you can run several commands:

  ```sh
  npm start
  ```
Starts the development server.

  ```sh
  npm run build
  ```
Bundles the app into static files for production.

  ```sh
  npm test
  ```
Starts the test runner.

  ```sh
  npm run eject
  ```
Removes this tool and copies build dependencies, configuration files and scripts into the app directory. If you do this, you can’t go back!

We suggest that you begin by typing:

  ```sh
  cd dockerized-react
  npm start
  ```

Happy hacking!

```sh
docker build -t dockerized-react .
```

```sh
docker run --name dockerized-react -p 3000:3000 dockerized-react
```

```sh
docker stop dockerized-react
docker stop dockerized-react
#docker rm -f dockerized-react
docker rmi dockerized-react
```

```sh
#docker port dockerized-react
```

```sh
docker compose up -d
docker compose down
docker compose logs -f
```