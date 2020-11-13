# в файле gitignore будут проигнорированы файлы
 # любое количество подкаталогов находящиеся в каталоге terraform игнорируется..
**/.terraform/*

 #  файлы с расширением tfstate игнорируются во всех каталогах

*.tfstate

 #  файлы с расширением *.tfstate и другими вариациями или продолжением расширений  

*.tfstate.*                  

 #  crash.log игнорируются во всех каталогах

crash.log 

 # файлы с расширением tfvars игнорируются во всех каталогах

*.tfvars

 # override.tf игнорируются во всех каталогах

override.tf 

 # override.tf.json игнорируются во всех каталогах 

override.tf.json 

 # файлы с совпаднием  override.tf например: 1override.tf, 2override.tf...

*_override.tf

 # файлы с совпаднием override.tf.json например:  1override.tf.json  2override.tf.json... 

*_override.tf.json

 # файл example_override.tf можно влючить в версионный контроль поставив знак'!' 
перед название файла пример: !example_override.tf 

!example_override.tf 

# файлы содержащие  в имени 'tfplan'

*tfplan*

 #  CLI файлы .terraformrc и terraform.rc игнорируются во всех каталогах
 
 .terraformrc 
  terraform.rc

