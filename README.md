# devops-netology
New code  

Будут игнорироваться файлы:  

1) Содержащие в своём пути ".terraform"
2) Файлы наименование которых заканчивается на .tfstate или сожержит .tfstate.
3) Файлы логов crash.log, а также файлы логов (формата .log) имеющие в названии crash.
4) Файлы имеющие имена которых заканчивается на .tfvars или же на .tfvars.json
5) Файлы override.tf и override.tf.json, а также заканчивающиеся на _override.tf или на _override.tf.json
6) Файл .terraform.tfstate.lock.info
7) Файлы .terraformrc и terraform.rc
