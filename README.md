### This is clone of Don's repo, since he discontinued the developement, and fix I have applied had to be done to continue using the plugin in newer ionic environments 

Issue fixed:
https://github.com/don/cordova-filechooser/issues/33
https://github.com/don/cordova-filechooser/issues/30


Cordova FileChooser Plugin

Requires Cordova >= 2.8.0

Install with Cordova CLI
	
	$ cordova plugin add https://github.com/luckylooke/cordova-filechooser.git

Install with Plugman 

	$ plugman --platform android --project /path/to/project \ 
		--plugin http://github.com/luckylooke/cordova-filechooser.git

API

	fileChooser.open(successCallback, failureCallback);

The success callback get the uri of the selected file

	fileChooser.open(function(uri) {
		alert(uri);
	});
	
Screenshot

![Screenshot](filechooser.png "Screenshot")

TODO rename `open` to pick, select, or choose.
