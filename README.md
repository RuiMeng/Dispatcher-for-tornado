Dispatcher for tornado

Ϊtornado��ܿ�����url�ַ��������뿪���и�ԭ����Լ���������ã����·��Ĭ������list����handlers = [(r"/post_path", PostHandler), (r"/del", DeleteHandler), (r"/home",HomeHandler)]������·�ɹ��򣬶����ڷ���http://localhst:8081/{controller}/{action} ��urlʱ��ʵ�ʵ���/appliaction/�����Ӧ���ֵ�controller������/application/controller/{controller}Controller.py
ģ��Ҳ��Լ����controller������ͬ����application/view���档
���ʵ����ģ��Լ����ͬ����ʵ�ʵĿ��������淵��{'__tpl_file': 'name'}���ɡ�

��Ŀ��tornado4.0����ͨ����

���ӣ�
1,����web server
    python main.py

2,����
    curl http://127.0.0.1:8081/test/action1



