
# Visit below sites for more content & tutorial
[MyBlog](https://arkit.co.in)

## Stop EC2 Instnace
- aws ec2 stop-instances --instance-id <INSTANCE-ID> --output json
- aws ec2 wait instance-stopped --instance-ids <INSTNACE-ID>

## Start EC2 Instnace
- aws ec2 start-instances --instance-id <INSTNACE-ID> --output json
- aws ec2 wait instance-running --instance-ids <INSTNACE-ID>
