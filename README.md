Description:
This tool just to quicly query the AWS API to get private IPs and their
corresponding name tag. The output is generated in CSV format.

Requisites:

* sudo apt install python-pip
* pip install boto3
* AWS API KEYs alredy loaded on your environment

Installation:
```
mkdir ~/bin
cp getip ~/bin/
echo "export PATH=$PATH:~/bin" >> ~/.bashrc
source ~/.bashrc
```

Usage:
```
$ getip web
100.1.0.76,web02
100.1.0.139,webservice
100.2.0.94,website
```
