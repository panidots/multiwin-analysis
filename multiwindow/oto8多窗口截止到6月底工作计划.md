# oto8多窗口截止到6月底工作计划

### 2019-03-27～2019~04-30
  - 多窗口应用适配
    - 微信适配
      - 1.聊天界面不显示窗口caption
      - 2.popupwindow弹出位置有问题
      - 3.窗口上方有遮挡，比如发现列表遮挡朋友圈选项
      - 4.朋友圈无法评论，点赞会滚动到第一条信息处
      - 5.聊天界面下拉，搜索小程序无法加载显示内容
      - 6.图片编辑，两边有透明区域
      - 7.尝试通过热修复方式，解决微信各版本通用bug
    - 微软office登录页面下窗口模式时没有标题栏
    - Sparkle Free在窗口模式下鼠标点击位置偏移
    - 2048左上角第一个方格总是显示被选中的蓝色，pcmark等应用也有此问题，oto2无此问题
    - 泰瑞呢、开心消消乐画面显示不全，默认窗口下一半不全的画面一半黑屏
    - 泰瑞呢、buttons and scissors、剪绳子、开心消消乐、模拟炒股等应用标题栏无手机桌面模式切换按钮
      - 应用本身方向不允许切换，切换会引起界面混乱
    - 狂野飙车8、央视影音、佳能打印打开闪退
      - 央视影音，java.lang.UnsatisfiedLinkError: dlopen failed: "/data/user/0/cn.cntvhd/files/libexec.so" has unexpected e_machine
      - 佳能打印：WifiP2pManager系统API更新后，此应用打开闪退，凤凰os7.1同样不可用。
    - bilibili首次打开时选择感兴趣的内容页面超出窗口
    
### 2019-05-01～05-31
  - 任务栏通知中心重构
  - 设置移植
  - 窗口快捷键移植
  - 首次配置移植
  - 权限管理器移植


### 2019-06-01～06-30
  - oto8 bug修复。
