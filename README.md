# Linux尚硅谷学习

#### 1.Linux内核  
Redhat(cenose,Redhat),Ubuntu,Suse,红旗Linux
#### 2.人机互动运作过程
应用软件（播放器）-shell层（解释层）-操作系统（Linux）-硬件(声卡)  
目前主要的操作系统有windows,Android
#### 3.Linux和unix的关系
说白了unix要收钱，先有的unix才有linux
#### 4.Linux和Windows的比较
开源就对了
#### 5.Linux目录结构
/dev 管理设备 /media目录  /root bin boot etc home var lib usr  
linux的系统是采用级层式的**树状目录结构**，在此结构中的最上层是根目录“/”，然后再次目录下再创建其他的目录  在linux世界中，一切皆文件    
**只有一个根目录，各个目录存放的内容是规划好，不用乱放文件**
|目录|作用|
|-|:------:|
|/bin|存放着最经常使用的命令|
|/sbin(/usr/local)|系统管理员使用的系统管理程序|
|/home|存放普通用户的主目录，在linux中每个用户都有一个自己的目录，一般以用户账号命名 |
|/root|系统管理员，也就是超级权限者的用户主目录|
|/lib|系统开机所需要最基本的动态连接**共享库**|
|/lost+found|一般为空，非法关机后会存放一些文件|
|**/etc**|**所有系统管理所需要的配置文件和子目录**|
|**/usr**|**很多用户的引用程序和文件都放在这个目录下**|
|**/boot**|**存放的是启动linux时使用的一些核心文件，包括一些连接文件以及镜像文件**|
|/proc|虚拟目录，系统内存的映射，访问这个目录来获取系统信息|
|/srv|service缩写，存放一些服务启动之后需要提取的数据，8能动|
|/sys|linux2.6内核的一个变化|
|/tmp|用于存放临时文件|
|/dev|类似于windows的设备管理器，把所有硬件用文件的形式存储|
|**/media**|**linux会自动识别一些设备，比如U盘，识别后，linux会把识别的设备挂在到这个目录下**|
|**/mnt**|**让用户临时挂载别的文件系统，比如说把d盘内容挂载到这，进去就可以看了**|
|/opt|给主机额外安装软件所摆放的目录，默认为空|
|**/usr/local**|**另一个给主机额外安装软件所安装的目录，一般是通过编译源码方式安装的程序**|
|**/var**|**这个目录中存放着在不断扩充着的东西，习惯将经常被修改的目录放在这个目录下，包括各种日志文件**|
|/selinux|安全子系统，它能控制程序只能访问特定文件|  
#### 6.vi和vim的使用
