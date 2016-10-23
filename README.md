# namevatar

## Install
	
	composer require "cyrrill/namevatar"
	
## Usage 	
	
### Generate a letter avatar 
 
 	$avatar = new Namevatar\Namevatar;
 	
 	$avatar
 		->generateFromName('Hello World', 40)
 		->saveAsPng('/path/to/file.png');
 		
### Save

	$letterAvatar
		->generate('J')
		->saveAsJpeg('/path/to/file.jpg');
	
