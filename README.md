## JavaScript is ...
a `dynamic`, `weakly typed`, `prototype-based` language with `first-class functions`.

## JS is Dynamic
```js
//Compilation and execution happen together.

var propMap = {
  val: "value", html: "innerHTML"
};

for(var fnName in propMap){
	
  $.prototype[fnName] = (function(prop){
  	return function(){
  	  return this[prop];
  	}
  })(propMap[fnName]);
}
```

## JS is Weakly Typed
```js
//Type associated with value, not variable.

var a = 1;
a = "one";
a = [1];
a = {one: 1};
```
## JS has 1st Class Functions
```js
//Treat like any object

var square = function(x){ return x*x },  //create

  	 mult = function(f1, f2){            // Return
    		return function(n){
      		return f1(n)*f2(n);
    		}
  	 },

  	 bigF = mult(square, square),        // ARG

value = bigF(2); // 16
```

## JS is Prototype Based
![image](https://user-images.githubusercontent.com/34129569/42721434-90dd4da2-8758-11e8-870e-276cbabef051.png)



JavaScript (JS) is a lightweight, interpreted or `JIT compiled programming language` with `first-class functions`. Most well-known as the scripting language for Web pages, `many non-browser environments` also use it, such as `node.js` and Apache `CouchDB`. JS is a `prototype-based`, multi-paradigm, dynamic scripting language, supporting object-oriented, imperative, and declarative (e.g. functional programming) styles. 


[Basic JavaScript](https://github.com/ps0305/Javascript-Algorithms-And-Data-Structures/tree/master/Basic%20JavaScript)

[ES6](https://github.com/ps0305/Javascript-Algorithms-And-Data-Structures/tree/master/ES6)

[Basic Algorith Scripting](https://github.com/ps0305/Javascript-Algorithms-And-Data-Structures/tree/master/Basic%20Algorithm%20Scripting)

[Basic Structures](https://github.com/ps0305/Javascript-Algorithms-And-Data-Structures/tree/master/Basic%20Data%20Structures)

[Debugging](https://github.com/ps0305/Javascript-Algorithms-And-Data-Structures/tree/master/Debugging)

[Algorithms Scripting](https://github.com/ps0305/Javascript-Algorithms-And-Data-Structures/tree/master/Basic%20Algorithm%20Scripting)

[Object oriented Programming](https://github.com/ps0305/Javascript-Algorithms-And-Data-Structures/tree/master/Object%20Oriented%20Programming)

[Functional Programming](https://github.com/ps0305/Javascript-Algorithms-And-Data-Structures/tree/master/Functional%20Programming)

[Intermediate Algorithm Scripting](https://github.com/TechnoBlogger14o3/Javascript-Algorithms-And-Data-Structures/tree/master/Intermediate%20Algorithm%20Scripting)

[Important CS Concepts](https://github.com/ps0305/Javascript-Algorithms-And-Data-Structures/tree/master/Important%20CS%20Concepts)


