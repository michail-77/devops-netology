# devops-netology
Добавил user.name


Локальные каталоги .terraform
файлы .tfstate
журналы crash.log
исключить все файлы .tfvars .tfvars.json , которые могут содержать конфеденциальные файлы
игнорировать файлы переопределения *_override.tf  *_override.tf.json
не исключать файлы отвечающие шаблоу example_override.tf
включить файлы tfplan, чтобы игнорироватьвывод команды: terraform plan -out=tfplan
игнорировать файлы конфигурации CLI .terraformrc и terraform.rc

