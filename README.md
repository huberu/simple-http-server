# simple-http-server

An quick and simple way to share files across a network, using Python's built in http.server.

	$ cd dir_to_share
	$ python3 -m http.server 8000

The Python script makes this easier, plus adds a convinience feature of opening the browser for you. It also solves buggy behaviour caused by Chrome pre-opening sockets that cause the http.server to hang until the request is made by the browser.

The instructions below create an execuatable Python file that lives in /usr/local/bin, so you can quickly get a local fileserver up and running by simply changing directory and typing "server". That's it!

Clone the repo: 

	$ git clone git@github.com:huberu/simple-http-server.git
    
Make the file executable 

	$ chmod +x simple-http-server/server

Move the file to /usr/local/bin

	$ sudo mv simple-http-server/server /usr/local/bin

Change directory to the desired location where you want to share files from, and run the server command

	$ cd files-to-share	
	$ server
	Serving HTTP on 0.0.0.0 port 8000 (http://0.0.0.0:8000/) ...
