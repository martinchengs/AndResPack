#使用方法
* 在local.properties文件中配置sdk.dir指向你自己的SDK位置
* 将你需要混淆资源的apk放入AndResCore/original文件夹中(white.txt可以直接删除)
* 将你的签名文件放入AndResCore文件夹中,并在config.xml中的sign节点配置好名称/密码/别名/密码
* 配置好白名单 是否使用7zip等等...
* 打开Terminal 输入 gradlew compressApp 执行Task结束后可以AndResCore/output中得到资源混淆后的apk文件和mapping文件
