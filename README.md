# Namevatar

## Install
	
	composer require "cyrrill/namevatar"
		
### Generate Namevatar 
 
 	$avatar = new Namevatar\Namevatar;
 	
 	$avatar
 		->generateFromName('Hello World', 40)
 		->saveAsPng('/path/to/file.png');

