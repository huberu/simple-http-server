# simple-http-server

An quick and simple way to share files across a network, using Python's built in http.server.

Instructions:
Clone the github repo: 

.. code:: console

	$ git clone git@github.com:huberu/simple-http-server.git
    
Make the file executable 

.. code:: console

	$ chmod +x /simple-http-server/server

Move the file to /usr/local/bin

.. code:: console
	
	$ mv /simple-http-server/server /usr/local/bin

Change directory to the desired location where you want to share files from, and run the server command

.. code:: console

	$ cd files-to-share

.. code:: console
	
	$ server
	Serving HTTP on 0.0.0.0 port 8000 (http://0.0.0.0:8000/) ...



