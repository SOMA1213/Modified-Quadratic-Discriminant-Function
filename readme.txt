MQDF�Υ饤�֥���äƤߤޤ���

auther:	Somada


Ver.1.0


--- �Ȥ��� ---

�ؽ����ʼ��������
./mqdf-train [option] training_data_dir dictionary_dir
[option]
-p �ѿ��Ѵ��Υѥ�᡼�� (  ~ 1 ) DEFAULT 1
   			���ϥǡ���������ͤ�������ϥ��顼
			

ǧ��
./mqdf-predict [option] dictionary_dir predict_datafile
[option]
-a alpha������ (0 ~ 1) DEFAULT 0.1
-k ���Ѥ����ͭ�٥��ȥ�ο� ( 0 ~ ���ϥǡ����μ����� )
-o ���ϥե�����



example:

bin/mqdf-train test/iris/train test/iris/dictionary
bin/mqdf-predict -o result.txt test/iris/dictionary test/iris/test/iris_all.libsvm
