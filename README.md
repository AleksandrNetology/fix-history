# Netology

# Home lesson 2.1
# описание файла Terraform.gitignore

**/.terraform/*
# всё содержимое директории .terraform игнорируется

*.tfstate 
# файлы с казанным расширение игнорируются

*.tfstate.*
# файл, содержащий в свём названии .tfstate. игнорируется

crash.log
override.tf
override.tf.json
.terraformrc
terraform.rc
# игнорировать указанные файлы

*_override.tf
*_override.tf.json
# файлы, оканчивающиеся так - игнорируются

# Новые ветки с помощью git switch -c <new_branch_name> <tag>

# Для переключения между верками (branch) используется git switch <имя ранее созданной ветки>. Далее, с помощью команды >ll или >ls -lh 
# проверяем содержимое рабочего каталога и приступаем к работе. По результатам оной делаем add и затем коммит этой ветки.
# Как её запушить в удалённый репозиторий?
# Да очень просто! Если выполнены комманды git add <filename> , а затем и git commin -m "comment", то просто делаем git push
# и изменённый файл отправится в соответсвующую ветку удалённого репозитория.