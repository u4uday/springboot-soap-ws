if executing in visual studio code, open ProducingWebServiceApplication.java class and click on Run that appears above the main method.

Navigate to the location of request.xml in terminal/command prompt and execute below command.
curl --header "content-type: text/xml" -d @request.xml http://localhost:8080/ws