# Known issues

- Using '.' or '-' in `test_userid` will cause errors: the created EC2 instances won't be able to be retrieved for stack deployment.
- On a BCD controller we can manage only one Terraform stack at a time.