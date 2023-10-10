## 从4.2版本换成了4.0版本
其实只需要修改setting.py, urls.py和game/admin.py, game/**, 然后makemigrations 和 migrate. 但是有时一点小问题就会卡人, 比如{, 比如urls.py忘记import include等等; 
修改.gitignore 忽略/static/但是为什么没有忽略掉呢?
