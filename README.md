# ZNTopWindow
在当前Window存在多个UITableView和UIScrollView时,系统的点击状态栏置顶的功能将无法使用,因为系统不知道应该返回哪一个控件的顶部,该代码实现了当前控制器存在多个含有UIScrollView控件属性的控制器时,点击当前的状态栏,将当前含有UIScrollView控件的控制器置顶的功能.在README文件中,复制粘贴到一个ZNTopWindow的类文件中,并在didFinishLaunchingWithOptions方法中调用ZNTopWindow.show()方法就好了,顶部区域的颜色自己可以设置.
