# What problem does using exports solve?  How does export differ from export default?  What is the benifit of using the Module system?

>It makes a module accessible to other parts of our code.

>Export just makes a file available to others that call it and export default is used when the import call has default values.  This will stop the Uncaught SyntaxError:.

>Code can be split into files of self contained functionality.  Modules help organize your code better.  Modules help with naming conflicts.  Code that references the module breaks when the module is changed of moved so it is immediately obvious.  Debugging is easier.