# Terraform error codes and what they may mean

## Error: timeout - last error: dial tcp nnn.nnn.nnn.nnn:22: i/o timeout
Often occurs when you have a terrform script that is then trying to do something to a virtual machine eg remote-exec or file provisioner.
Check network security groups, firewalls etc to make sure that access is allowed from your local ip address
