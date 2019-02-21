Hello!

Your task is to use the provided assets to create the web app displayed in the Web_Programmer_Test.pdf spec.

Please break down how much time you spend on what.

Please include the full react project as a zip in a buildable state and if possible a compiled version we can run locally.


Subscribe to Newsletter Endpoint

[POST] REQUEST URL: http://dev.datechnologies.co/Tests/scripts/add-email.php


Field 	Value           	Description
email 	test@datechnologies.co 	Email

RESPONSE:
{
    status :  success,
    message :  Generic Success
} 


If possible have the login / signup function using these endpoints.

SIGNUP

[POST] REQUEST URL: http://dev.datechnologies.co/Tests/scripts/user-signup.php

Field 		Value 		            Description
username 	testuser 		        Unique Username
password 	Test123 		        Password
email 		test@datechnologies.co 		Unique Email


RESPONSE:

{
    "user_id": 16,
    "user_email": "test@datechnologies.co",
    "user_username": "testuser",
    "user_is_active": 1,
    "user_profile_image": "http://dev.datechnologies.co/Tests/images/taylor_avatar.png",
    "user_last_active_epoch": 1544680026,
    "user_creation_epoch": 1544713200,
    "user_is_new": 1,
    "user_token": "6dd4737a8b7ec61313ae5e900420d46815e1d13b2902be71b97a8fbf1f421a3e"
}

LOGIN
[POST] REQUEST URL: http://dev.datechnologies.co/Tests/scripts/user-login.php


Field 		Value 			        Description
email 		test@datechnologies.co 	Email
password 	Test123 		        Password


RESPONSE:

{
    "user_id": 16,
    "user_email": "test@datechnologies.co",
    "user_username": "testuser",
    "user_is_active": 1,
    "user_profile_image": "http://dev.datechnologies.co/Tests/images/taylor_avatar.png",
    "user_last_active_epoch": 1544680026,
    "user_creation_epoch": 1544713200,
    "user_is_new": 1,
    "user_token": "6dd4737a8b7ec61313ae5e900420d46815e1d13b2902be71b97a8fbf1f421a3e"
}