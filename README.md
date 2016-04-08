#WooConf 2016 - Restful WooCommerce

To prepare for the exercises, register with the assigned test area below. We will give you access to WooCommerce.


##Test areas
The class will be assigned a test area and a 

* https://growdevelopment.net/woo1/
* https://growdevelopment.net/woo2/
* https://growdevelopment.net/woo3/
* https://growdevelopment.net/woo4/
* https://growdevelopment.net/woo5/

Product IDs
99,96,93,90,60,67,60,73

##Exercise 1
In this exercise you will get access to a sample WooCommerce store.
Create API credentials.
Do a simple get on a product using a client, or a library.

`GET /wc-api/v3/products/<id>`

##Exercise 2
In this exercise you will update a product
Log into the WordPress backend to see a product to update.

`PUT   /wc-api/v3/products/<id>`

##Exercise 3
In this exercise you will create an order
Use your own email as the customer
Set the order to completed status
Show us the email sent to you

`POST  /wc-api/v3/orders`



### Tools
* [CocoaRestClient](http://mmattozzi.github.io/cocoa-rest-client/) - A free, easy to use Mac OS X GUI client for interacting with the API, most useful when your test store has SSL enabled.
* [RESTClient, a debugger for RESTful web services](https://addons.mozilla.org/en-US/firefox/addon/restclient/) - Free Firefox add-on.
* [Advanced REST client](https://chrome.google.com/webstore/detail/advanced-rest-client/hgmloofddffdnphfgcellkdfbfbjeloo) - Free Google Chrome extension.

### Official libraries

* [Node.js](https://www.npmjs.com/package/woocommerce-api)
* [PHP](https://packagist.org/packages/automattic/woocommerce)
* [Python](https://pypi.python.org/pypi/WooCommerce)
* [Ruby](https://rubygems.org/gems/woocommerce_api)







### Resources

Documentation
https://docs.woothemes.com/document/woocommerce-rest-api/

API Documentation
http://woothemes.github.io/woocommerce-rest-api-docs/

Source code
https://github.com/woothemes/woocommerce/tree/master/includes/api
