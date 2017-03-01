### Micro RedHat using cloud Formation

#### Settings

* 22 and 80 as inbound

#### To Run

```bash
aws cloudformation create-stack --stack-name micro-redhat --template-body file:////home/ec2-user/AWS/micro-redhat.json --parameters ParameterKey=KeyName,ParameterValue=b612
```
