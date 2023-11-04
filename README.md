

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
- my_btn_lazy_var_swift_block

7.dire(目录)
8.date(时间)
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
- my_imageCreate_swiftUI_block

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
39.navigationItem(导航条Item)
40.lock(lock多线程锁)
41.keyboard(keyboard键盘展示与消失)
42.setting(settingApp的偏好设置)
43.convert(convert不同坐标系转换)
44.rect(rect包含/交互操作)
45.textField(textField相关的操作)
46.attributeStr(attribute富文本)
47.methodSinInvocation(methodSinInvocation方法签名+命令模式)
48.keypath(keypath操作)
49.view(view操作)
50.observer（observer添加kvo观察者）

51.bundle(bundle包资源)
- my_bundleSub_swift_func

52.shadow(shadow阴影)
53.runtime(runtime方法交换)
54.collectionView(collectionView创建)
55.stackView(StackView创建)
56.dataSave(数据持久化)
57.kvcOper(kvc操作)
58.checkShow(检查view是否可视)
59.blockLocalVarCreate(局部变量block创建)
60.deprecated(deprecated代码或API有版本限制)
61.theme(主题色设置)
62.sharedInstance(单例)
- my_sharedInstance_swift_block

63.pointer2pointer(坐标转换)
64.available(平台使用范围判断)
- my_available_swift_block


65.masnory(自动布局)
- my_masnory_animation_swift_block


66.image(图片)
- my_imageCreate_waterMark_swift_func

67.swiftUI部分
- my_textLabelCreate_swiftUI_block
- my_listNavigationBarCreate_swiftUI_block
- my_uikit2swiftUI_swiftUI_block
- my_VStack_HStack_swiftUI_block
- my_publishd_observed1_state2_combin_swiftUI_block
- my_swiftui2uikit_swiftUI_block
- my_scale_rotation_animation_swiftUI_block
- my_transition_animation_swiftUI_block
- my_scrollview_swiftUI_block
- my_present/push_swiftUI_block
- my_picker_menu/wheel/segmented_swiftUI_block
- my_picker_datePicker_swiftUI_block
- my_protocals_swiftUI_txt
- my_glouble_environment_swiftUI_block
- my_lifeCircle_event_swiftUI_block
- my_binding_data_view_swiftUI_block

68.viewController基本模板
- my_vc_swift_block


***
##### OC部分
1.dispatch(大中枢并发)
- my_dispatchAfter_oc_block
- my_dispatchMainQueue_oc_block
- my_dispatchGlobalQueue_oc_block
- my_dispatchgroup_oc_block
- my_dispatchgroupEnter/leave_oc_block

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
- my_buttonGetter_oc_block
- my_btnArrayCreate_oc_func

7.dire(目录)
- my_dirCache_oc_block
- my_dirDocu_oc_block
- my_dirAll_oc_block

8.date(时间)
- my_dateformat_oc_block
- my_datecalendar_oc_block

9.property(属性创建)


10.predicate(谓词)
- my_predicate_oc_block

11.screenShot(截屏)

12.suStr(子字符串)

13.imageView(imageView创建)
- my_imageViewCreate_oc_block
- my_imageViewGetter_oc_block

14.label(label创建)
- my_labelCreate_oc_block
- my_labelGetter_oc_block

15.layer(layer创建)
- my_layerLine_oc_block
- my_layerBorder_oc_block

16.layerGradient(layerGradient渐变色图层创建)
- my_gradientLayer_Color_oc_block

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
- my_timer3kind_oc_block
- my_timerCreate_oc_block

21.log(log使用)
- my_log_oc_block

22.selector(selector选择子)

23.weakSelf(weakSelf弱引用)
- my_weakSelf_oc_block

24.width(width视图宽高)
- my_widthS+heightS_oc_block
- my_widthV+heightV_oc_block
- my_widthFix_oc_block

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

39.navigationItem(导航条Item)
- my_navigationItemRight_oc_block
- my_navigationItemSearchBar_oc_block

40.lock(lock多线程锁)
- my_lock_oc_block

41.keyboard(keyboard键盘展示与消失)
- my_keyboardNotif_oc_block
- my_keyBoardHide_oc_block

42.setting(settingApp的偏好设置)
- my_settingOpenState_oc_block
- my_settingPageForApp_oc_block

43.convert(convert不同坐标系转换)
- my_pointconvert_oc_block

44.rect(rect包含/交互操作)
- my_rectContains_oc_block

45.textField(textField相关的操作)
- my_textFieldCreate_oc_block

46.attributeStr(attribute富文本)
- my_attributeStr_oc_block
- my_attriStrClickYY_oc_block
- my_attributeParagraphStyle_oc_block

47.methodSinInvocation(methodSinInvocation方法签名+命令模式)
- my_methodSinInvocation_oc_block

48.keypath(keypath操作)
- my_keypath_oc_block

49.view(view操作)
- my_viewGetter_oc_block

50.observer（observer添加kvo观察者）
- my_observer_kvo_oc_block

51.bundle(bundle包资源)
- my_bundleSub_oc_block

52.shadow(shadow阴影)
- my_shadow_oc_block

53.runtime(runtime方法交换)
- my_runtimeExchangeMethod_oc_block
- my_runtime_associated_block
- my_runtime_create_class_block

54.collectionView(collectionView创建)
- my_collectionView_oc_block

55.stackView(StackView创建)
- my_stackViewCreate_oc_block

56.dataSave(数据持久化)
- my_datakeychain_oc_func
- my_dataUserdefault_oc_func
- my_dataArchive_oc_func
- my_dataPlist_oc_func

57.kvcOper(kvc操作)
- my_kvcOper_oc_block

58.checkShow(检查view是否可视)
- my_checkShow_oc_block

59.blockLocalVarCreate(局部变量block创建)
- my_blockCreat_LocalVar_block

60.deprecated(deprecated代码或API有版本限制)
- my_code_dep_oc_block
- my_api_dep_oc_block

61.theme(主题色设置)
- my_theme_navbar_oc_func

62.sharedInstance(单例)
- my_sharedInstance_oc_func

63.pointer2pointer(坐标转换)
- my_pointer_to_otherPointer_oc
64.available(平台使用范围判断)
65.masnory(自动布局)
66.image(图片)

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
- my_structure_swiftUI_txt

4.property(property定义)
- my_propert_oc_txt

5.keyboard(keyboard键盘类型)
- my_keyboardtype_txt

6.clang(clang编译器说明)
- my_clangUndecSelector_txt
- my_ifdebug_release_txt

7.baseVC(vc模版)
- my_tableViewBaseVC_oc_txt

8.timeExecuLong(timelong代码执行时长)
- my_timeExecuLong_oc_txt

9.arm(arm设备架构)
- my_arm_txt

10.mark(mark常用的标示)
- my_mark5_txt

11.warn(warn注释或添加代码警告)
- my_warn_txt

12.macro(macro系统常有的宏)
- my_macro_oc_txt
- my_macro_ifdef_txt


13.预编译
- my_build_condition_swift_txt

14.oc中Block,swift中闭包的定义
- my_oc/block_swift/closure_txt

15.算法
- my_algorithm_bubblingSort1_c_func
- my_algorithm_selectSort2_c_func
- my_algorithm_insertSort3_c_func
- my_algorithm_shellSort4_c_func
- my_algorithm_quickSort5_c_func
- my_algorithm_mergeSort6_c_func
- my_algorithm_binarySort7_c_func
- my_algorithm_heapSort8_c_func

16.版本号判断
- my_version_if_oc/swift_txt

