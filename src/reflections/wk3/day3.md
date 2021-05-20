# What are the two common operations that we will set in the handler?  What do you have to make sure you are doing with every Get to ensure the value does not become undefined?  What are some of the benifits of the proxy object that we are using in our structure for applications?

>Get and Set.  

>We set a trap by providing two parameters, the object itself and the property being accessed.

>Useful for keeping data private, validation, can redefine operations. 