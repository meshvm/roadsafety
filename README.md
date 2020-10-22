# roadsafety
Scheduling API which accepts Date-Time and a URL as a parameter.


When the API is called, a task will be scheduled. A GET request (no parameters needed) should be sent on the URL  specified (second parameter), when the current Date-Time matches the one specified in the Date-Time parameter (first parameter).
The GETrequest on the URL parameter will only return a status code, and no response body, when we will judge the task. 
Along with the API endpoints specified in each of the sets, a separate ping endpoint must be created, to know that the server is alive. 
Whenever a GET request is sent to the '/ping' endpoint, the server must return a JSON "{ "status":"OK"}". 
Applicants are also advised to write a short documentation of their code, which must include details on how to call each endpoint and a sample response of the server. 
Applicants will be judged upon the extent of completion of the task, the efficiency and The neatness of the code and, the quality of the documentation provided. 


