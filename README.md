angular2-test
=============



install typescript and tsd package manager
---

```
npm install -g typescript@^1.5.0-beta
npm install -g tsd@^0.6.0
```

to compile
----

```
tsc --watch -m commonjs -t es5 --emitDecoratorMetadata app.ts
```


to start server
------

install `http-server` package (`npm install -g http-server`)

and start from root of project by executing `http-server`


