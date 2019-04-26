# simple-http-server

An quick and simple way to share files across a network, using Python's built in http.server.

	$ cd dir_to_share
	$ python3 -m http.server 8000

If you don't think you'll remember this, the instructions below will do the same thing by just typing "server".

Clone the repo: 

	$ git clone git@github.com:huberu/simple-http-server.git
    
Make the file executable 

	$ chmod +x simple-http-server/server

Move the file to /usr/local/bin

	$ mv simple-http-server/server /usr/local/bin

Change directory to the desired location where you want to share files from, and run the server command

	$ cd files-to-share	
	$ server
	Serving HTTP on 0.0.0.0 port 8000 (http://0.0.0.0:8000/) ...
