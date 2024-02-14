5.a : docker pull httpd
b : docker images
d : docker run -p 80:80 -v .\htdocs:/usr/local/apache2/htdocs/ httpd 
e : docker create -p 80:80 --name test httpd
	docker cp .\htdocs test://usr/local/apache2/
	
6.a : docker build .
b : docker run 'image_id' 
c : La procédure 6 est la plus automatisée c'est la meilleure façon de faire à grande échelle, la procédure 5.  est plus à reserver pour des tests de petite échelle

7.a: docker pull mysql:5.7
	 docker pull phpmyadmin
