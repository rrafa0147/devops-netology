# � ����� gitignore ����� ��������������� �����
 # ����� ���������� ������������ ����������� � �������� terraform ������������..
**/.terraform/*

 #  ����� � ����������� tfstate ������������ �� ���� ���������

*.tfstate

 #  ����� � ����������� *.tfstate � ������� ���������� ��� ������������ ����������  

*.tfstate.*                  

 #  crash.log ������������ �� ���� ���������

crash.log 

 # ����� � ����������� tfvars ������������ �� ���� ���������

*.tfvars

 # override.tf ������������ �� ���� ���������

override.tf 

 # override.tf.json ������������ �� ���� ��������� 

override.tf.json 

 # ����� � ����������  override.tf ��������: 1override.tf, 2override.tf...

*_override.tf

 # ����� � ���������� override.tf.json ��������:  1override.tf.json  2override.tf.json... 

*_override.tf.json

 # ���� example_override.tf ����� ������� � ���������� �������� �������� ����'!' 
����� �������� ����� ������: !example_override.tf 

!example_override.tf 

# ����� ����������  � ����� 'tfplan'

*tfplan*

 #  CLI ����� .terraformrc � terraform.rc ������������ �� ���� ���������
 
 .terraformrc 
  terraform.rc

