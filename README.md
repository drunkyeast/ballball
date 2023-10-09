## 从4.2版本换成了4.0版本
其实只需要修改setting.py, urls.py和game/admin.py, game/**, 然后makemigrations 和 migrate. 但是有时一点小问题就会卡人, 比如{, 比如urls.py忘记import include等等; 
所以某次提交改变了很多admin下面的文件
