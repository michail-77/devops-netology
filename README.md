# devops-netology
Добавил user.name

Файлы, которые будут проигнорированы в будущем благодаря добавленному .gitignore:
1. Локальные каталоги .terraform
2. файлы .tfstate
3. журналы crash.log
4. все файлы .tfvars .tfvars.json , которые могут содержать конфеденциальные файлы
5. игнорировать файлы переопределения *_override.tf  *_override.tf.json
6. не исключать файлы отвечающие шаблоу example_override.tf
7. включить файлы tfplan, чтобы игнорировать вывод команды: terraform plan -out=tfplan
8. игнорировать файлы конфигурации CLI .terraformrc и terraform.rc

добавлена ветка fix
