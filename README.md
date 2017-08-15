## ����
����һ������Mitmproxy��Arachni�ı���ʽɨ������
* arachni
* celery
* mitmproxy

![��������ͼ.png](https://github.com/jjf012/PassiveScanner/images/process.png)

����Ϊ���ܹ���`celery`������windows���棬��ѡ��İ汾��3.1.25��
redis��Ϊcelery��broker�������������롣
ͨ��`celery -A scan worker --loglevel=info`����worker��
`proxy.py`��Ĭ�϶˿���8080��

![mysql.png](https://github.com/jjf012/PassiveScanner/images/mysql.png)

�ο�����
[����Arachni�����ں�ɨ��ƽ̨](http://bobao.360.cn/learning/detail/3533.html)
[wyproxy](https://github.com/ring04h/wyproxy)
[Arachni](https://github.com/Arachni/arachni/wiki/REST-API)

## English
This is a passive scanner based on Mitmproxy and Arachni.
* Arachni
* Celery
* Mitmproxy

! [Basic flow chart .png] (https://github.com/jjf012/PassiveScanner/images/process.png)

Which in order to be able to `celery` run on windows, I chose the version is 3.1.25.
Redis as celery broker and set the password.
Start worker with `celery -A scan worker - loglevel = info`.
The default port for `proxy.py` is 8080.

! [Mysql.png] (https://github.com/jjf012/PassiveScanner/images/mysql.png)

Reference link
[Based on Arachni build black box scanning platform] (http://bobao.360.cn/learning/detail/3533.html)
[Wyproxy] (https://github.com/ring04h/wyproxy)
[Arachni] (https://github.com/Arachni/arachni/wiki/REST-API)