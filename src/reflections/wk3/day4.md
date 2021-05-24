#  What patterns does the Observer Pattern seek to resolve?

#  What are the three mechanisms of the Observer Pattern?

#  Reflect on the proxy objects of the bcw-template and your understanding of the observer pattern.  Explain how the "magic" of the bcw-template uses the two concepts to manage and update the dom.


>  One to many, one-way, and event-driven.


>  Subscribe, unsubscribe and broadcast.


>  The proxy objects are validated and added.  This is done with the event listeners.  All of the data is compartmentalized and protected. We recieve data from the dom through the controller.  After it has been manipulated in Services through the AppState, it is sent back to the dom through the Controller. 





https://github.com/CameronBlanchard/sporting-goods