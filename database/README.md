# db manager ����

�켱�� �����ϰԸ� ���� ���� ����� ������Ʈ �� ��� ��� �ϰڽ��ϴ�.   

database/config ���� ���� ��, �� �ȿ� secrets.json ������ �����մϴ�.  
json ������ ���� ������ ����� �մϴ�.  

{  
    "host": <ins>database ip</ins>,  
    "user": "root",  
    "password": <ins>database password</ins>,  
    "port": 3306  
}  

��ɾ�� ���� ���� �ΰ����� ������, ���� ������Ʈ �����Դϴ�.  

1. �����ͺ��̽� �� ���̺� ����  
python db_manager.py --command create  
  
2. ���̺� ����  
python db_manager.py --command delete  