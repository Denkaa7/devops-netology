# devops-netology

В директории terraform будут проигнорированы следующие файлы
- всё, что лежит в директории .terraform/
- Файлы с расширением *.tfstate; файлы, имеющие в имени *.tfstate.*
- Файл с именем crash.log; файл, в имени которого начало и конец совпадают с crash.*.log
- Все файлы с расширением *.tfvars и файлы, с именем на конце которых  *.tfvars.json
- Файлы override.tf и override.tf.json. Файлы, на конце которых *_override.tf и *_override.tf.json
- Файл .terraform.tfstate.lock.info
- Файлы .terraformrc и terraform.rc

Change file