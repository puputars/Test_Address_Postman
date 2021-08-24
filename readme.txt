1. First, please update "data-address.csv" at username and password column with username and password that have never been created. So you can sign up with rest API.


2. Then, run the automation test rest API with this command. 
(Make sure you already installed node, newman, and newman-reporter-htmlextra)

newman run Test_Address.postman_collection.json -d data-address.csv -e GIV.postman_environment.json --delay-request 20 -r htmlextra


3. Report HTML will created at newman folder.
