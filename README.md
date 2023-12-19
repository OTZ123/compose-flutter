# compose-flutter

Flutter源码编译设置config.gradle中FlutterShell为true
并且将flutter-shell防治在与该项目同级目录下且保证有.android和Flutter子目录
--parent
  ｜--${thisProject}
  ｜--flutter-shell
    |--.android
    |--Flutter