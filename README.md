# label_auto_text

A label widget that appears on other widgets, and its internal text adapts to the label size

Revised from https://github.com/flyou/label_view
## Getting Started
To use this packages, add label_auto_text as a dependency in your pubspec.yaml file.

    import 'package:label_auto_text.dart';
## Example

    @override
      Widget build(BuildContext context) {
        return LabelViewDecoration(
            size: Size(80.0, 80.0),
            labelColor: Colors.red,
            labelAlignment: LabelAlignment.leftTop,
            useAngle: true,
            labelText: "Hot",
            labelTextColor: Colors.white,
            child: _builderItem()
        );
      }
* labelAlignment: LabelAlignment.leftTop,
![LabelAlignment.leftTop](https://github.com/HappyGhostz/label_auto_text/blob/master/Screenshot/one.png)

* labelAlignment: LabelAlignment.leftBottom,
![LabelAlignment.leftBottom](https://github.com/HappyGhostz/label_auto_text/blob/master/Screenshot/two.png)

* labelAlignment: LabelAlignment.rightTop,
![LabelAlignment.rightTop](https://github.com/HappyGhostz/label_auto_text/blob/master/Screenshot/three.png)

* labelAlignment: LabelAlignment.rightBottom,
![LabelAlignment.rightBottom](https://github.com/HappyGhostz/label_auto_text/blob/master/Screenshot/four.png)