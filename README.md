To launch the program locally:
Transfer the given HTML code into an index.html file.
Navigate to index.html in a browser.
To create the Docker image and use it to launch a container:
In the directory where index.html is located, create a Dockerfile.
To access the directory with the Dockerfile and index.html, open a terminal.
To start a container using the image, use the following command after the image has been successfully built:


Docker run 8080:80 -d -p just-do-it-app


Using a web browser, navigate to http://localhost:8080 to see the Docker application.
Decisions or presumptions reached throughout the development process:
I utilized JavaScript, CSS, and basic HTML for mobility and simplicity.
