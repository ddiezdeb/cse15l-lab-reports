Below is my StringServer I created, that takes my queries and outputs them.

![Image](StringServerEmpty.png)
An image of my empty server.

![Image](StringServer1.png)
An image of my server after entering the query `/s=Hi`. The method `public String handleRequest(URI url)` checks the url and if the path includes "add-message", the string after "=" is added to a list. Then a for loop outputs a string containing all added messages where each added message is numbered and separated from the next message by a newline.

![Image](StringServer2.png)
An image of my server after entering another query. Again, the method `public String handleRequest(URI url)` checks the url and if the path includes `/add-message`, the string after "=" is added to a list. Then a for loop outputs a string containing all added messages where each added message is numbered and separated from the next message by a newline.

![Image](StringServerJavaPic.png)
And here is the code for my StringServer that I implemented in order to have the server output the query.



Below is my directory holding the private key, id_rsa and the publick key, id_rsa.pub and me SSHing without having to input login information.
![Image](directoryID.png)
Accessing the directory throught the terminal.

![Image](SSHAuto.png)
Above is a picture of my terminal as I log into ieng6 without having to input a username or password.


In Week 2 and 3 I was able to learn about servers, and got a better insight into how servers can be set up, implemented or accessed. 
I learned about different parts of the URL like the domain, path, query and the anchor. This gave me a better idea of how a server functions since I was able to take code to run a server and modify it to implement functions. I did this by using the query to take in user input and modifying the input in order to change what the server was outputting.
