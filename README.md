Api Auth ReST - Basic Authentication for codeigniter rest server
========

Concept by Kamal Mustafa &amp; Implement and enhanced by aa6my

- Basic auth mean the client send Authorization headers in form of 'Basic ' + base64_encode(username + ':' + password)

My concept

- sha1(password.customer === customer.password)


/application/config/rest.php 
- $config['rest_auth'] = 'basic'; 
- $config['auth_source'] = 'library'; 
- $config['auth_library_class'] = 'Api_auth';
- $config['auth_library_function'] = 'login'; 
