# CS312 Final
Final project for System Administration -- Minecraft server using AWS EC2 and Terraform

Author: Julian (Jules) Brinkley

Instructor: Alexander Ulbrich

Date: June 14, 2023

# Introduction
\<placeholder text\>

# Prerequisites
\<placeholder text\>

# Usage
Usage is quite easy! Simply open a bash terminal, navigate to the directory containing 'main.tf', and run the following command:

```bash
./tf_commands.sh
```

After around 5 minutes, the script should finish and print out the public IP address of the server. Connect however you choose (nmap -sV -Pn -p T:25565 \<instance_public_ip\>, Minecraft client, etc.), and enjoy!

# Destruction
To destroy the server and its resources, run the following command:

```bash
terraform destroy
```

# Sources
https://developer.hashicorp.com/terraform/tutorials/aws-get-started

https://github.com/HarryNash/terraform-minecraft

https://github.com/gerhalt/mining-camp

CS312 class resources (particularly the Terraform lab)