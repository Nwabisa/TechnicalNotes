# Linkie Technical Notes

## Workshops

* [Functions & Objects](./workshops/functions_and_objects_slides.html)
* [Useful algorithms](./workshops/useful_algorithms.md)
* Useful algoritms using functions (lodash)
* How does a web application work?
* Others?
* Which test is much more better to work on, Mocha/Qunit?
* Why do we write test?

## Keep updated

To ensure your fork have the latest changes from this repository.

[Look at these instructions](https://help.github.com/articles/configuring-a-remote-for-a-fork/)

You need to create an upstream repository for your fork.

## Notes

Notes on things I learned & snippets of code that will make my life easier

### How to print a string to the console

```javascript
// how do I print to the console again?
//how do i print hello world to the screen?
console.log("hello World!");
```

### How Do i write if conditional statement
```javascript
//how do i write if statement?
if (condition) {
   //do this
}else
//do something else
}
```
### How to test with mocha
* create a folder ferry
* run mocha, the test should fail
* create folder test and the again run mocha it should pass by now
```javascript

//here is an example of a test that is passing
var assert = require("assert");

describe("In the ferry kata", function(){
	it("I should be able to create cars", function(){
		//Assemble
		//Action
		//Assert
		assert.equal("car", "car");
	});
});

//here is an example of a test that is failing
describe("In the ferry kata", function(){
it("I should be able to see penguins", function(){
		//Assemble
		//Action
		//Assert
		assert.equal("car", "penguins");
	});
});
```
add more here...

### If things get to long...

* [Todo something useful](notes/my_file.md) A short description here
* [Create a basic Express app](notes/my_file.md) How to get going with express
* [Linkstar_file](Linkstar_file.md) Linkie's stuff
