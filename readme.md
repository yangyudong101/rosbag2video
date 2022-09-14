#### 压缩话题和原始话题均可以转换

转换命令如下：

```shell
python rosbag2video.py [--fps 25] [--rate 1] [-o outputfile] [-v] [-s] [-t topic] bagfile1 [bagfile2] ...
```

具体命令示例为：

```shell
python rosbag2video.py -o yanjiuyuan.mp4 -t /galaxy/img ./0803-2.bag
```

正常显示如下：

![image-20220831095744567](/home/dong/.config/Typora/typora-user-images/image-20220831095744567.png)



参考来源：

[CSDN参考来源一：ros bag包转mp4视频](https://blog.csdn.net/Boys_Wu/article/details/125675254?ops_request_misc=&request_id=&biz_id=102&utm_term=bag%E8%BD%ACmp4&utm_medium=distribute.pc_search_result.none-task-blog-2~all~sobaiduweb~default-5-125675254.nonecase&spm=1018.2226.3001.4187)

[CSDN参考来源二：rosbag转化为.mp4格式视频](https://blog.csdn.net/BAIFOL/article/details/125715959)