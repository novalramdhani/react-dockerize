# React Dockerize
React.js web app with docker container example.

Visit express dockerize backend in [this link.](https://github.com/novalramdhani/express-dockerize)

# How to use
First, clone this repository
```bash
git clone git@github.com:novalramdhani/react-dockerize.git

cd react-dockerize
```

Next step, install all dependencies in `node_modules`.
```bash
npm install && npm update
# or with yarn
yarn && yarn upgrade
```

Last step, run local development server.
```bash
npm run start
# or with yarn
yarn start
```

Congrats!, your application running in `localhost:3000`

### With docker environment.
Run docker compose with this command.
```bash
docker-compose up
# running in background
docker-compose up -d
```

If you down docker compose, you can.
```bash
docker-compose down
```