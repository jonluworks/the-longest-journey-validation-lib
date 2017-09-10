# the-longest-journey-shared

This is a place for easy sharing of code between the game client and the backend server. The code for the client and server used 
to be in one git repository, but it got confusing to look at since they both used babel etc. I am in the process of refactoring the
code into two separate repositories and using this library for shared validation code.

I am using babel so I can write ES6+ code and transpile it down to ES5 for node package compatibility.
