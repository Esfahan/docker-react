# React with Docker

## Installation
### build

```
$ docker-compose build
```

### Create React App

```
$ ./bin/create-react-app ${YOUR_APP_NAME}
```

If you use TypeScript

```
$ ./bin/create-react-app-with-typescript ${YOUR_APP_NAME}
```

### Submodule

```
$ git submodule add -f https://github.com/Esfahan/react-tutorial.git code/react-tutorial
```

```
$ git submodule update -i && git submodule foreach git pull origin master
```

### yarn install

```
$ ./bin/yarn-install ${YOUR_APP_NAME}
```

## Usage
### yarn start

```
$ docker-compose up -d
```

### Browse
http://localhost:3000


## react-tutorial
- https://github.com/Esfahan/react-tutorial
