# 4640-w11-lab-start-w25

## Running the Ansible configuration

### Requirements:

- You may need install the aws_ec2 plugin with the command `ansible-galaxy collection install amazon.aws`
- When you run the `ansible-playbook` command it may tell you if there are any missing packages such as Boto and Botocore3. You can install these by running `pip3 install botocore boto3`

1. Ensure you have the necessary packages installed
2. `cd` into the directory that has your Ansible playbook file.
3. Run `ansible-playbook -i inventory/aws_ec2.yml playbook.yml`

You can then see your website being served in through your browser.
![Week 11 Lab](Week%2011%20lab.png)
