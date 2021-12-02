# Typescript 

Superset of JavaScript. 

Dynamic vs Static: 

Both rely on types. 
* Dynamic "duck" typing - if it looks like a duck, talks like a duck, and walks like a duck - it is most likely a duck. 
* Dynamic = Forgiving, great for web browser object model. 
* Static type - aim to catch errors before the code is ran, no room for mistakes. 
* Static = Rigid, promotes stability and maintainability. 


To define the type use the syntax `: <type>`
* `function speak(value)` -> `function speak(value : string)` 
* `let someValue` -> `let someValue : string `
* `function something()` -> `function something() : string `