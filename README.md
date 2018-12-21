# iOS-my-CodeSnippets

***
**使用方法**
CodeSnippets目录已经存在时
第一种使用方式：

1.打开终端，执行命令：`cd ~/Library/Developer/Xcode/UserData/CodeSnippets`

2.在此目录下执行命令:`git clone https://github.com/zhfei/iOS-my-CodeSnippets.git`


**CodeSnippets目录还没有创建时**

1.打开终端，执行命令：
```
git clone git@github.com:zhfei/iOS-my-CodeSnippets.git ~/Library/Developer/Xcode/UserData/CodeSnippets
```

注意：因为工程clone下来后，自带文件夹`iOS-my-CodeSnippets`，还需要做简单的处理，最终目的是让代码库的所以++资源文件+.git文件++都放到`~/Library/Developer/Xcode/UserData/CodeSnippets`文件夹下


***
==代码块命名规则制定中...==
```
//代码块命名规则
//1.基本规范
my_名词 动作_swift
my_名词 动作_oc
//2.添加block。func补充说明
my_名词 动作_swift_func
my_名词 动作_oc_block
```

##### 代码块类型

###### swift部分
1.dispatch(大中枢并发)
- my_dispatchAfter_swift_block
- my_dispatchAfterCancle_swift_func
- my_dispatchgroup_swift_block
- my_dispatchMainQueue_swift_block

2.serial(序列化功能)
- my_serialDataToJson_swift_func
- my_serialJsonToStr_swift_func

3.realm(Realm数据库操作)

4.alertVC(系统弹框)
- my_alertVC_swift_block

5.bezier(贝塞尔曲线)
- my_bezier_swift_block

###### oc部分
1.dispatch(大中枢并发)
- my_dispatchAfter_oc_block
- my_dispatchMainQueue_oc_block
- my_dispatchGlobalQueue_oc_block
- my_dispatchgroup_oc_block

2.serial(序列化功能)
3.realm(Realm数据库操作)
- my_realmCreate_oc_block
- my_realmEncry_oc_block
- my_realmMigrat_oc_block
- my_realmNotifi_oc_block

4.alertVC(系统弹框)
- my_alertVC_oc_block

5.bezier(贝塞尔曲线)
