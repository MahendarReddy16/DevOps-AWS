## Lock and Key are Pair and Firewall ##

Key pair = public key(.pub) and private key(.pem)

-> Public Key will stay inside the server and while authenticating user should send his username and the private key instead of password.

To Generate Keys Command:(use gitbash)
```
ssh -keygen -f <filename>
```

Publice Key extension:
```
ssh -rsa <random-code> lap_suername@laptop_name
```
## Path in AWS 
EC2 --> Keypairs --> Import public key pairs


### Firewall/Security Group ###
Firewall in aws is nothing but the security group

## Path in AWS
EC2 --> Security Group -->create SG 