# AWS-Email-Enumerator

This Python script uses boto3 to check whether an email address is associated with an AWS account. It performs the following operations:

1- Creates a bucket named <your chosen name --bucket>  
2- Enables ACL usage on the bucket  
3- Checks if an email has an associated AWS account  

## Prerequisites
1- Python 3.6+  
2- AWS credentials configured (via AWS CLI or environment variables)  
3- Proper permissions in the AWS account  
4- Boto3 library  

```sh
python3 -m venv virtual
source virtual/bin/activate
pip3 install boto3
```

```sh
python aws-email-root-validator.py --email your.email@example.com

python aws-email-root-validator.py --file email-list.txt
```
![image](https://github.com/user-attachments/assets/3ccdf7e3-2ee2-4622-ba9a-a2ff3f1d5e9f)

![image](https://github.com/user-attachments/assets/ba35f2a7-0ff6-4407-9674-68e2483bdf59)

