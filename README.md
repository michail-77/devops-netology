# devops-netology
Добавил user.name

Файлы, которые будут проигнорированы в будущем благодаря добавленному .gitignore:
Локальные каталоги .terraform
файлы .tfstate
журналы crash.log
все файлы .tfvars .tfvars.json , которые могут содержать конфеденциальные файлы
игнорировать файлы переопределения *_override.tf  *_override.tf.json
не исключать файлы отвечающие шаблоу example_override.tf
включить файлы tfplan, чтобы игнорировать вывод команды: terraform plan -out=tfplan
игнорировать файлы конфигурации CLI .terraformrc и terraform.rc
добавлена ветка fix
