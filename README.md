# WZXJianShuPopDemo
仿简书、淘宝等等的View弹出效果，已封装好，使用简单
<div>
</div>
###效果图
![image](https://github.com/Wzxhaha/WZXJianShuPopDemo/raw/master/JianShuPop.gif)
<div>
</div>
###使用方法
* 创建一个VC继承```WZXPopViewController```
* 然后在VC中使用```- (void)createPopVCWithRootVC:(UIViewController *)rootVC andPopView:(UIView *)popView```方法
   * rootVC传入下层View的VC，popView传入弹出的View

###Demo
Demo内的```TestViewController```为测试的VC，使用该动画的方法可以看这个VC

###更新
* 2016.1.21 
   *  更新怎么加导航栏
   *  更新怎么把点击方法加到自己创建的Btn上
* 2016.2.24
   *  感谢[简书:反方向de钟](http://www.jianshu.com/users/4f002d4502b5/timeline)的反馈，修改了不能改变popview大小的bug

###PS
更加详细的讲解在[简书:WzxJiang](http://www.jianshu.com/p/a697d2a38b3c)
<div>
</div>
喜欢请给Star!

