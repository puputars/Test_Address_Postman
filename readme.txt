First, please update "data-address.csv" at username and password column with username and password that have never been created. So you can sign up with rest API.

Then, run the automation test rest API with this command. 
(Make sure you already installed node, newman, and newman-reporter-htmlextra)
Here's the tutorial :
https://www.cuelogic.com/blog/postman-tutorial-for-automation

newman run Test_Address.postman_collection.json -d data-address.csv -e GIV.postman_environment.json --delay-request 20 -r htmlextra


Report HTML will created at newman folder.
