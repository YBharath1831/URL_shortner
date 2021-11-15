URL Shortener

It is a simple website that shortens the given URL, it produces a short code that is attatched to the base url. It helps in redirecting the produced short url to orginal URL

Before executing the new.php file,follow the below steps
1.Download and install XAMPP SERVER
2.Create a database in your server
3.Create a table by executing following SQL Commands
 CREATE TABLE IF NOT EXISTS <code>url_shorten</code> 
		(
	id int(11) NOT NULL AUTO_INCREMENT PRIMARY KEY,
	url tinytext NOT NULL,
	short_code varchar(50) NOT NULL,
	hits int(11) NOT NULL,
	added_date timestamp NULL DEFAULT CURRENT_TIMESTAMP
		);
4.Edit the code according to the created database credentials and table configuration
5.Host the website and finally you will your shortened URL as well as the list of Urls that are already converted.
