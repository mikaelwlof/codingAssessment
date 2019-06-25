#Code Assignment
						
##Overview
						
The assignment is to build a small, full stack javascript application. The application is a simple game which can display a random outcome generated on the server.
												
##Client		
-  ES6 is not mandatory but encouraged		
-  The user must be able to trigger a request for outcome to the server	
-  The outcome must be displayed to the user using the provided graphical resources (Symbol_0.png, Symbol_1.png,...)
-  The type of win must be displayed to the user (No Win, Small Win, Big Win)
								
##Server
-  Server must be a Node.js application (hint: use an express server)
-  Server must be written in ES6
-  Server must be able to serve needed resources to client.
-  Server must be able to receive requests from client and return an outcome (three random integers between 0-5).
								
There must be three types of outcomes: No Win, Small Win, Big Win. Two equal integers constitutes a Small Win. Three equal integers constitutes a Big Win.
