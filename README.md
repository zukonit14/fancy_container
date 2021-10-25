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
# Fancy Containers

Fancy container package lets you add a beautiful gradient container to your Flutter app.

## Installation 

1. Add the latest version of package to your pubspec.yaml (and run`dart pub get`):
```yaml
dependencies:
  zuk_fancy_containers: ^0.0.1
```
2. Import the package and use it in your Flutter App.
```dart
import 'package:fancy_container/fancy_containers.dart';
```

## Example
There are a number of properties that you can modify:

 -  height
 - width               
 - title 
 - subtitle
 - gradient (color1 and color2)

<hr>

<table>
<tr>
<td>

```dart
class FancyScreen extends StatelessWidget {  
  const FancyScreen({Key? key}) : super(key: key);  
  
  @override  
  Widget build(BuildContext context) {  
    return Scaffold(  
      body: Center(  
        child: const FancyContainer(  
          title: 'Hello World',  
          color1: Colors.lightGreenAccent,  
          color2: Colors.lightBlue,  
          subtitle: 'This is a new package',  
        ),  
      ),  
    );  
  }  
}
```

</td>
<td>
<img  src="https://user-images.githubusercontent.com/53579386/126896556-911d4778-04cd-49bf-b32a-01a6eb3b0155.jpeg"  alt="">
</td>
</tr>
</table>

## Next Goals

 - [x] Add onTap for functions.
 Now, you can specify the onTap and specify a function.
 
 - [x] Change font and color style for text.
 Change color by specifying `textcolor` and `subtitlecolor` properties.
 
 - [ ] Add more containers to the package.