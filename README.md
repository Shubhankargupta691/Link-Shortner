# Link-Shortner

A link shortener is a web application that takes a long URL and generates a shorter, more user-friendly URL that redirects to the original URL. 

Here's how the program works:

    We import the pyshorteners library, which provides an easy way to shorten and expand URLs using a variety of URL shortener services.
    We create an instance of the Shortener class, which we'll use to interact with the URL shortener service.
    We call the short() method of the Shortener instance, passing in the long URL we want to shorten. This method returns the shortened URL.
    We call the expand() method of the Shortener instance, passing in the shortened URL we want to expand. This method returns the original long URL.
    We print the short URL and long URL to the console.

You can replace tinyurl in the code above with other supported URL shortener services like bitly, adfly, is.gd, etc., depending on which service you want to use. You can also pass additional options to the short() method to customize the behavior of the URL shortener, such as setting a custom alias or expiration date.
