���� �� 
     httpserver��
       ��ȡhttp���� 
       ����http����
       �������͸�WebFrame
       ��WebFrame���շ�������
       ��������֯ΪResponse��ʽ���͸��ͻ���

     WebFrame��
       ��httpserver���վ�������
       ������������߼���������ݴ���
          * ��̬ҳ��
	  * �߼�����
       ����Ҫ�����ݷ�����httpserver

     ������ �� 1. ����httpserver��Ӧ�ô�������ģʽ
               2. ��������϶�
	       3. ԭ����httpserver���Դ��������   webFrame

��Ŀ�ṹ��  
           |--httpserver --HttpServer.py (������)    |             --settings (httpserver����) |   
  project--|
           |
           |
           |--WebFrame   --static ����ž�̬��ҳ��
	                 --views.py �� Ӧ�ô������ 
                         --urls.py �����·�ɣ�
			 --settings ��������ã�
			 --WebFrame.py (���������)
