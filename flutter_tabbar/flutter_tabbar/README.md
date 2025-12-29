<!-- 
This README describes the package. If you publish this package to pub.dev,
this README's contents appear on the landing page for your package.

For information about how to write a good package README, see the guide for
[writing package pages](https://dart.dev/guides/libraries/writing-package-pages). 

For general information about developing packages, see the Dart guide for
[creating packages](https://dart.dev/guides/libraries/create-library-packages)
and the Flutter guide for
[developing packages and plugins](https://flutter.dev/developing-packages). 
-->

由于此版本的代码太低 只能通过插件方式依赖，不然2.0后的空安全全部都改成空安全很费事。
TODO: xxxxx.

## Getting started

TODO: flutter_tabbar: ^1.0.0

## 
to `/example`    
```dart
Custom.TabBar(
                                   controller: this._controller2,
                                   indicatorSize: Custom.TabBarIndicatorSize.label,
                                   indicatorColor: Colors.white,
                                   labelStyle: TextStyle(
                                     fontSize: 16.0,
                                     fontWeight: FontWeight.bold,
                                   ),
                                   unselectedLabelStyle: TextStyle(fontSize: 13.0),
                                   indicatorWeight: 3.0,
                                   isScrollable: true,
                                   indicatorPadding: EdgeInsets.fromLTRB(0.0, 0.0, 0.0, 5.0),
                                   tabs: [
                                     Tab(text: '动态'),
                                     Tab(text: '热门'),
                                     Tab(text: '附近'),
                                     Tab(text: '颜值'),
                                     Tab(text: '音乐'),
                                   ],
                                 ),
```

## Additional information

TODO: xxx
