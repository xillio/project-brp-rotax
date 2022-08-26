---------------------
Installation
---------------------

The OpenText API is a library. It has to be included in a robot as follows:

`include src.main.xill.com.xillio.opentext.API;` 

Once included in a robot, all the public API functions can be accessed within this particular robot.

To be able to use the OpenText API functions, access to an OpenText Content Server is required.
The server details have to be provided in a parameter for any of the public API functions. 

Example of the *server* parameter:

    var server = {
    	"apiUrl": "http://server/cs.exe/api/v1/",
    	"credentials": {
    		"username": "username",
    		"password": "password"
    	}
    };

  

---------------------
Scope
---------------------

The API provides a set of functions that contain OpenText-specific API calls. The API is to be employed in any migration project that involves a migration *from*  (export) or *to* (import) an OpenText Content Server.

