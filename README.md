# fish


A fish flock AI VR demo for Unreal Engine 4 *(This is an unoptimized version( check out branch master for the latest code ))*
> 一个基于虚幻4的鱼群AI的VR demo *(这是个没有优化过的版本( 最新的代码请切到master分支查看 ))*


![github_fish_flock_ai.png](https://ooo.0o0.ooo/2016/10/18/58060a188d281.png)

## Video Preview 
* Watch the [Video Preview](http://v.youku.com/v_show/id_XMTc2NTM4MjkyMA==.html)

	> 查看 [视频演示](http://v.youku.com/v_show/id_XMTc2NTM4MjkyMA==.html) 

## Download & Play

#### **Download**
* Download [MyFish.exe (Win64)](http://pan.baidu.com/s/1qYbBrHU)

	> 下载  [MyFish.exe (Win64)](http://pan.baidu.com/s/1qYbBrHU) 玩玩 

#### **How to play**

- *VR* : 

	*(My Device is HTC Vive)*

	* Motion Controller FaceButton1 => Move forward

		` 手柄圆盘上键                  => 往前移动`

	* PC's KeyBoard Arrow UP and Down    => Move faster or slower

		` 电脑键盘的上下箭头键          =>  调整移动速度`

	* Hold Motion Controller Trigger Down     => Attract fishes

		` 按住手柄扳机键                    => 吸引鱼群`

- *PC* :

	* EQ        =>  Up & Down

		` EQ  键     =>  上下 `

	* WASD         =>  Basic movement 

		` WASD 键     =>  基本的移动指令(前后左右) `

	* Hold Left Mouse Button Down  =>  Attract fishes

		` 按住鼠标左键           =>  吸引鱼群`

	* Arrow UP and Down  =>  Move faster or slower

		` 上下箭头键         =>  调整移动速度`



## About This 


* Unreal Engine Version

	4.13

* Read [Craig Reynolds's thesis](http://www.red3d.com/cwr/boids/)  

	> 查看 [Craig Reynolds的论文](http://www.red3d.com/cwr/boids/) 


* This project implements a new flocking Ai algorithm, with 2 components : 

	> 算法简要

	* Separation : every fish will try to steer away from their neighbors 

		`分离性 ：每条鱼都会与周围的鱼保持距离 `

	* Following the leader : every fish will try to follow its leader

		`跟随一个领头者 ： 每条鱼都会跟随一个领头者`

* Other features :

	> 其他特性

	* Avoiding enemies.

		`躲避敌人`

	* Run **1200** fishes at the same time

		`可以同时运行 1200 条鱼儿`

	* Wander when no leader

		`当没有领头者的时候随机漫游`