in package.json,

```
"bin" : {
	"clidemo" : "./index.js"
}
```

in index.js

```
console.log("hello world");
```

"clidemo" is our custom command, when run it, "index.js" executed

i have published this simple demo on npm, so there are 2 ways to run demo

#1. create a module by yourself, then
---------------------------
run

	npm install -g
you will install your own module (this one) into node-global

simple call

	clidemo
output

	hello world

#2. install this package to global from npm
--------------------------
run

	npm install -g node-clidemo
run

	clidemo
output on cli

	hello world
awesome, it works ^^