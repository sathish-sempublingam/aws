# aws
aws-s3 CLI-commands

create ec2
install the awscli
sudo apt install unzip
curl "https://awscli.amazonaws.com/awscli-exe-linux-x86_64.zip" -o "awscliv2.zip"
unzip awscliv2.zip
sudo ./aws/install
aws --version   ---> to be check version cli

configure access key
create access key
aws configure
ID:

aws s3 ls --> listout s3 bucket

touch file{1..10}.txt ---> create the file

aws s3 cp file.txt s3://bucket-name  ---> server one file only copy to s3 bucket

aws s3 cp .(all file ".") s3://bucket-name  --recursive   ---> server multiple file copy to s3 bucket
aws s3 cp . s3://my-bucket-ec2-123  --recursive


aws s3 ls my-bucket-ec2-123 ---> s3 bucket listout files
