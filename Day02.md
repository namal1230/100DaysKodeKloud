aws ec2 describe-security-groups

aws ec2 create-security-group --group-name test01 --description "this is first security group"

aws ec2 describe-security-groups --group-name test01

aws ec2 delete-security-group --group-name test01

aws ec2 authorize-security-group-ingress --group-name test01 --protocol tcp --port 22 --cidr 0.0.0.0/0

<img width="1147" height="812" alt="Screenshot 2026-08-15 223031" src="https://github.com/user-attachments/assets/70758c04-e376-4a9b-a1e5-0c1390a145fb" />

<img width="1080" height="695" alt="Screenshot 2026-08-15 223701" src="https://github.com/user-attachments/assets/cb90f7c7-4af8-4158-a65d-596786d0fd61" />
