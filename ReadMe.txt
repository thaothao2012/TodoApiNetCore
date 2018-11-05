//create api app
1: create .net core app with API temlate
	- add Models folder: create database Context
		 register database context : use dependency injection container
	- add Controller : getData, getDataById, create item, update item, delete item
2: routing url path : 	[Route("api/[controller]")]
    			[ApiController]
3: return values : return "JSON"
4: launch app : can use POSTMAN to view 
5: call the web API with jQuery : gettodo, add, updata, delete.