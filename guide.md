# Configuring AWS CLI on ubuntu machine 

```
1 sudo apt install snapd
2 sudo snap install aws-cli --classic
3 aws --version
4 aws configure
5 aws configure list

```

# Making ansible to work with AWS

```
1 sudo apt install python3-venv
2 python3 -m venv ansible_venv
3 source ansible_venv/bin/activate
4 pip install boto3 botocore
5 python -c "import boto3; print(boto3.__version__)"
6 deactivate
```
