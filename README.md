# zxingLibs
android 实现 二维码快速扫描功能

二维码图片识别功能还未实现(以实现)

会在近期内实现二维码扫描功能的(以实现)

引用方式：
compile 'org.lqos.zxing:zxings:1.1.6'

继承CaptureActivity 实现几个方法 getSurfaceView()、getViewfinderView()后，

自动开启扫描二维码

重写该方法： handleDecode(Result result, String barcode) 得到扫描结果和二维码截图保存路径

