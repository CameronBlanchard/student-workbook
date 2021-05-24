#  What is the purpose of encapulation?  

#  What are some of the problems with closures and the uderscore prefix?  

#  How do we create private variables in a ES6 class?  Why would you do that?

>  To make sure that the bundle is restricted to bundles outside of it


>  Denoting private private properties and methods with the underscore method can be problematic because many ignore the convention and that can lead to breaking changes.  It can expand the attack surface.  If using that convention you are relying on the user to understand not to use it.


>  We create them indside a function that is contained in a function.  This enforces true encapulation.


https://github.com/CameronBlanchard/vending-machine
