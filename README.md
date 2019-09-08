#### Connect to elasticsearch using python

### Prerequisites:
	- python3
	- ubuntu 18.04
    - java1.8

### Install python elasticsearch module
	- Save elasticsearch in requirement.txt and run following command
        - sudo pip3 install -r requirement.txt

### Install elasticsearch on ubuntu
    - sudo apt update
    - sudo apt-get install apt-transport-http
    - wget -qO - https://artifacts.elastic.co/GPG-KEY-elasticsearch | sudo apt-key add -
    - sudo add-apt-repository "deb https://artifacts.elastic.co/packages/7.x/apt stable main"
    - sudo apt update
    - sudo apt install elasticsearch
    - To start Elasticsearch process
        - sudo /etc/init.d/elasticsearch start
        - sudo /etc/init.d/elasticsearch status
    - Test setup
        - curl -X GET "http://localhost:9200/?pretty"


