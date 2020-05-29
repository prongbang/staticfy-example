# Staticfy Example

### Project structure

```bash

```

## Run with docker-compose

```bash
$ docker-compose up
```

- Running

```bash
app_staticfy_1  | 
app_staticfy_1  |    ______       __  _     ___    
app_staticfy_1  |   / __/ /____ _/ /_(_)___/ _/_ __
app_staticfy_1  |  _\ \/ __/ _ `/ __/ / __/ _/ // /
app_staticfy_1  | /___/\__/\_,_/\__/_/\__/_/ \_, / 
app_staticfy_1  |                           /___/
app_staticfy_1  | 
app_staticfy_1  | -> staticfy serving /publisher on :9000
```

## Run with golang binary

```
$ go get -u github.com/prongbang/staticfy
$ staticfy
```

- Running

```bash
   ______       __  _     ___    
  / __/ /____ _/ /_(_)___/ _/_ __
 _\ \/ __/ _ `/ __/ / __/ _/ // /
/___/\__/\_,_/\__/_/\__/_/ \_, / 
                          /___/

-> staticfy serving /publisher on :9000
```

## Listening

- [http://localhost:9000/publisher/test/test.txt](http://localhost:9000/publisher/test/test.txt)
- [http://localhost:9000/publisher/hello.txt](http://localhost:9000/publisher/hello.txt)
- [http://localhost:9000/publisher/html/hello.html](http://localhost:9000/publisher/html/hello.html)
- [http://localhost:9000/publisher/image/wiremock.png](http://localhost:9000/publisher/image/wiremock.png)