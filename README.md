# First_commit

# Local .terraform directories
**/.terraform/* - Игнорирование локльной директории terraform

# .tfstate files 
*.tfstate
*.tfstate.*  - Файлы состояния инфраструктуры 

# Crash log files
crash.log  - Файлы логов ошибок (краш)
crash.*.log

# Exclude all .tfvars files, which are likely to contain sensitive data, such as
# password, private keys, and other secrets. These should not be part of version 
# control as they are data points which are potentially sensitive and subject 
# to change depending on the environment.
*.tfvars  - конфиг, со значением переменных 
*.tfvars.json    

# Ignore override files as they are usually used to override resources locally and so
# are not checked in
override.tf
override.tf.json - файлы предопределения 
*_override.tf
*_override.tf.json

# Include override files you do wish to add to version control using negated pattern
# !example_override.tf

# Include tfplan files to ignore the plan output of command: terraform plan -out=tfplan
# example: *tfplan*

# Ignore CLI configuration files
.terraformrc - файл, содержащий адрес зеркал 
terraform.rc