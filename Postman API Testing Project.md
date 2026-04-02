Postman API Testing Project



This project demonstrates basic API testing using Postman. It includes tests for multiple endpoints, validation of responses, and handling of negative scenarios.



Test Scenarios -

1\. Get All Posts

* Verify status code is 200
* Validate response is an array



2\. Get Single Post

* Verify status code is 200
* Validate post ID
* Check required fields



3\. Negative Test (Invalid ID)

* Verify API handles invalid requests properly



4\. Create Post (POST)

* Verify status code is 201
* Validate response contains new post ID
* Confirm request data is returned correctly



4\. PUT Request

* Verifies the request was successful
* Ensures the title in the response matches the updated value sent in the request
* Ensures the body in the response matches the updated value sent in the request



5\. DELETE Request

* Verifies the delete request was successful
* Confirms the API returns an empty object {} as expected for deletion





How to Run -

* Download from my github repository
* Import the collection into Postman
* Run each request individually or use a Collection Runner



Skills Demonstrated

* API request handling
* Writing test scripts in JavaScript
* Validating JSON responses
* Handling edge cases

