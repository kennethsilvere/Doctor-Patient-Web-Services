DOCTOR PATIENT WEB SERVICES PROJECT

This is a restful web services project which provides CRUD operations involving doctor/patients information. 
The general idea is that we have an information management system where we can use web services 
to create, read, update and delete various information items as listed below. 
We use text files for storing input data rather than a database for both ease of use and focus on web services. 
Our base data set consists of a string for a doctor name along with a List of patients assigned to that doctor. 
A Patient class has at least two string properties: a name and an insurance card number. 
The system or hospital can have many doctors where each doctor as mentioned earlier is associated with a List of patients.

A user/administrator will be able to do the following operations: 
(1) Get a list of all doctors along with their patients in XML and plain text. 
(2) Get a list of an individual doctor and his/her patients in XML and plain text: (given an id for the individual doctor) 
(3) Add or create a new doctor along with his/her patients to the existing list. 
(4) Update (modify) a doctor’s name only on an existing list of doctor-patients: (given an id for the doctor along with a new name). 
(5) Delete or remove an existing doctor along with his/her patients: (given an id for the doctor).

JAX-RS API using Jersey is used for this project. For input data, two sample files are provided for reading each doctor’s name 
followed by a number of patients in one file (drs.db) and list of patients’ information (name and insurance card number) 
for each corresponding doctor in a separate file (patients.db) .

This web service should be deployed to a Tomcat server via an ant script. 
For testing purposes and verification screenshots, you should use “curl” utility and a browser.
