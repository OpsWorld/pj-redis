
һ��Monitor
     1.Ϊÿ��redisʵ������һ����ʱ�̣߳������ռ�Info���ݣ����洢���£�
1. Info ����ȡʧ���Ǳ���Ϊ NULLֵ
����ȡ�������ݵ����洢��������ʾ
2. Memory ��peak��current
3. command�� ���β�ֵ������
4.Status �� down��Master��detail����slave��detail������ֻ�������α��ʱ��¼
5.Hit rate
6.keys��expires
7.�������� expired��evicted

    2.����������
          ÿ3sȡһ�Σ���ôÿСʱ���ݣ�1200��һ��Info����1.5K����ôһ��ʵ��1Сʱ1.8M����ô20��ʵ��һ��������ݣ�860M��
     Infoȫ�����ݻ��ǲ�׼��ȫ������һ�ݣ�����redis�ڴ�ռ�ã�����ʹ��sqllite��ѹ������

         ��ô������Info����������һ��200�ֽڣ���ôһ��������120M����������7�죻��Monitor��ʱ��顣

      redis����ZSET���棬ʹ��UNIX ʱ���Ϊscore����������ʹ��json���档

����Web���棺
    Overview + Live

����ʹ�÷�ʽ
	redis-live.conf Ϊjson��ʽ����
	�ռ��������ݴ洢Ŀǰֻ��ʹ��redis
	
	������
	�������̣� redis-monitor.py Ϊ��ʱ�ռ�����
				redis-live.py ��վ�㣬�˿�Ϊ��8888
	
��װ������
	python2.7
	tornado
	redis-py
	python-dateutil-2.1
	jinja2
	werkzeug
	