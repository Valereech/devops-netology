# devops-netology
### First modify
### Second modify

Ответ по п.4 для второго коммита.  
На данный момент к коммиту отмечен файл `.gitignore`, но он пустой. Таким образом, ничего не игнорируется. Каталог `terraform` - untracked. Внутри него файл `.gitignore`, в котором описаны шаблоны для всех файлов для игнорирования в будущем, а именно:  
`**/.terraform/*` - все локальные .terraform каталоги;  
`*.tfstate` и `*.tfstate.*` - все файлы с расширением `.tfstate`, а также файлы, содержащие в имени `.tfstate` с любым расширением;  
`crash.log` - файл в каталоге `terraform`;  
`*.tfvars` - файлы с любым именем и с расширением `.tfvars` каталога `terraform`;  
`override.tf`, `override.tf.json` - файлы каталога `terraform`;  
`*_override.tf`, `*_override.tf.json` - файлы каталога `terraform`, содержащие в имени `override` и/или `_override.tf` и с расширениями `.tf`, `.json`;  
`.terraformrc` - файлы каталога `terraform`, с расширением `.terraformrc`;  
`terraform.rc` - файл каталога `terraform`.  
После выполнения п.5 задания для второго коммита, эти файлы и будут игнорироваться, хоть их и нет сейчас в репозитории.

ДЗ 2.2 Задание 4. Добавлена строчка в IDE PyCharm