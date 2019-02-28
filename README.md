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
//2.添加block,func,txt补充说明
my_名词 动作_swift_func
my_名词 动作_oc_block
my_名词 动作_oc_txt
```
block: 方法内的代码块
func: 完整的方法
txt:工程配置变量，VC结构分割

##### 代码块类型

***
##### swift部分
1.dispatch(大中枢并发)
- my_dispatchAfter_swift_block
- my_dispatchAfterCancle_swift_func
- my_dispatchgroup_swift_block
- my_dispatchGroupEnter_swift_block
- my_dispatchMainQueue_swift_block
- my_dispatchSemaphoreCreate_swift_block

2.serial(序列化功能)
- my_serialDataToJson_swift_func
- my_serialJsonToStr_swift_func

3.realm(Realm数据库操作)

4.alertVC(系统弹框)
- my_alertVC_swift_block

5.bezier(贝塞尔曲线)
- my_bezier_swift_block

6.button(按钮创建)
- my_btnCreate_swift_block

7.dire(目录)
8.dateFormatter(格式化时间)
- my_dateFormat2Date_swift_func
- my_dateFormat2Str_swift_func

9.property(属性创建)

10.predicate(谓词)
11.screenShot(截屏)
- my_screenShot_swift_func
- my_screenShotToPhoto_swift_func

12.suStr(子字符串)
- my_suStr_swift_func

13.imageView(imageView创建)
- my_imageViewCreate_swift_block

14.label(label创建)
- my_labelCreate_swift_block
- my_labelAutoWidth_oc_block

15.layer(layer创建)
- my_layerCreate_swift_block

16.layerGradient(layerGradient渐变色图层创建)
- my_layerGradientCreate_swift_block

17.tableView(tableView代理)

18.uiFactory(uiFactor创建)
- my_uiFactory_swift_func

19.enum(enum枚举定义)

20.timer(timer创建使用)
- my_timerAfterCancle_swift_block

21.log(log使用)

22.selector(selector选择子)
- my_selector_swift_block

23.weakSelf(weakSelf弱引用)

24.width(width视图宽高)
- my_widthV+heightV_swift_block
- my_widthS+heightS_swift_block

25.regex(regex正则表达式)
- my_regex2str_swift_func
- my_regex2bool_swift_func

26.anim(anim动画)
- my_animRotation_swift_block
- my_animRotationBase_swift_block

27.class(class自定义类)
- my_classStrInt_swift_func

28.IBOutIBActio(属性、动作连线)
29.CGContext(核心绘图，常用绘制)
30.nibLoad(nib文件加载)
31.viewController(控制器)

32.navigationController(导航控制器)
- my_naviBarHide_swift_func
- my_gesCancle_swift_func

33.tabBarController(tabBar控制器)
- my_tabbarHide_swift_block

34.appearUISet(UI控件全局统一设置)

35.drawRect(画图)

36.textField(textField常用代理方法)

37.textView(textView常用代理)

38.refreshUI(mj_refresh控件添加)



***
##### OC部分
1.dispatch(大中枢并发)
- my_dispatchAfter_oc_block
- my_dispatchMainQueue_oc_block
- my_dispatchGlobalQueue_oc_block
- my_dispatchgroup_oc_block

2.serial(序列化功能)
- my_serialDataToJson_oc_func
- my_serialJsonToStr_oc_func

3.realm(Realm数据库操作)
- my_realmCreate_oc_block
- my_realmEncry_oc_block
- my_realmMigrat_oc_block
- my_realmNotifi_oc_block
- my_realmModelUse_oc_block

4.alertVC(系统弹框)
- my_alertVC_oc_block

5.bezier(贝塞尔曲线)
- my_bezierBorder_oc_block

6.button(按钮创建)
- my_btnCreate_oc_block

7.dire(目录)
- my_dirCache_oc_block
- my_dirDocu_oc_block

8.dateFormatter(格式化时间)
- my_dateformat_oc_block

9.property(属性创建)


10.predicate(谓词)
- my_predicate_oc_block

11.screenShot(截屏)

12.suStr(子字符串)

13.imageView(imageView创建)
- my_imageViewCreate_oc_block

14.label(label创建)
- my_labelCreate_oc_block

15.layer(layer创建)
- my_layerLine_oc_block
- my_layerBorder_oc_block

16.layerGradient(layerGradient渐变色图层创建)

17.tableView(tableView代理)
- my_tableViewAll_oc_block
- my_tableViewParter_oc_block
- my_tableViewDelegate_oc_func
- my_tableCellAutoHeigh_oc_block


18.uiFactory(uiFactor创建)
- my_uiFactory_oc_func

19.enum(enum枚举定义)
- my_enum+Type_oc_block

20.timer(timer创建使用)

21.log(log使用)
- my_log_oc_block

22.selector(selector选择子)

23.weakSelf(weakSelf弱引用)
- my_weakSelf_oc_block

24.width(width视图宽高)
- my_widthS+heightS_oc_block
- my_widthV+heightV_oc_block

25.regex(regex正则表达式)
- my_regex2bool_oc_func

26.anim(anim动画)
- my_animMoveBase_oc_block
- my_animGroupBase_oc_block

27.class(class自定义类)

28.IBOutIBActio(属性、动作连线)
- my_ibOut_ibAction_oc_block

29.CGContext(核心绘图，常用绘制)
- my_cgcontextStr_oc_block

30.nibLoad(nib文件加载)
- my_nibload_oc_block

31.viewController(控制器)
- my_rootVC_oc_block

32.navigationController(导航控制器)
- my_naviBarHide_oc_func
- my_gesCancle_oc_func
- my_navigationBarSet_oc_block

33.tabBarController(tabBar控制器)
- my_tabbarHide_oc_block

34.appearUISet(UI控件全局统一设置)
- my_appearUISet_oc_block

35.drawRect(画图)
- my_drawCircle_oc_block

36.textField(textField常用代理方法)
- my_textFieldDelegate_oc_func

37.textView(textView常用代理)
- my_textViewDelegate_oc_func

38.refreshUI(mj_refresh控件添加)
- my_refreshUIAdd_oc_block

***
##### 工程设置，文档部分

1.arc(arc类文件设置，搜索路径)
- my_arc_txt

2.note(note注释)
- my_note_txt

3.structure(structure结构)
- my_structure_oc_txt
- my_structureView_oc_txt
- my_structureCN_oc_txt
- my_structureHeardCN_oc_txt
- my_structure_swift_txt

4.property(property定义)
- my_propert_oc_txt

5.keyboard(keyboard键盘类型)
- my_keyboardtype_txt

6.clang(clang编译器说明)
- my_clangUndecSelector_txt
- my_clangifdebug_txt

7.baseVC(vc模版)
- my_tableViewBaseVC_oc_txt