First, please update "data-address.csv" at username and password column that have never been created. So you can sign up with rest API.

Then, run the automation test rest API with this command. 
(Make sure 

newman run Test_Address.postman_collection.json -d data-address.csv -e GIV.postman_environment.json --delay-request 20 -r htmlextra


Report HTML will created at newman folder.
