# gradient_progress_bar

A Flutter package for both android and iOS which provides Gradient progress indicator

## Usage

[Example](https://github.com/urvashik-7span/gradient_progress_bar/main/example/lib/main.dart)

To use this package :

* add the dependency to your [pubspec.yaml](https://github.com/urvashik-7span/gradient_progress_bar/main/pubspec.yaml) file.

```yaml
  dependencies:
    flutter:
      sdk: flutter
    gradient_progress_bar:
```
## Screenshots

![Screenshot_1](https://github.com/urvashik-7span/gradient_progress_bar/blob/main/assets/screenshot_1.png?raw=true)

### How to use

```dart
class Test extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return Container(
      child:Center(
        child: Column(
          mainAxisAlignment: MainAxisAlignment.center,
          children: const <Widget>[
            GradientProgressIndicator([
              Color(0xffF68270),
              Color(0xffF1C358),
              Color(0xffEFDE62),
              Color(0xffE5F3BE),
              Color(0xffCDE8F1),
              Color(0xffDDC5EE),
              Color(0xffF2E0F9),
            ], 0.8)
          ],
        ),
      ),
    );
  }
}
```
