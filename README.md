project for api gateway using consul
before running application make sure consul service is up and runinng 
if not please perform below steps to start consul server in you machine

download zip file from https://developer.hashicorp.com/consul/install
unzip download zip file
run this command in cmd
consul agent -dev -client=0.0.0.0
after server start open below url in browser
http://localhost:8500/ui/dc1/services
