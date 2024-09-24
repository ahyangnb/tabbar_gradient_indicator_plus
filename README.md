# Tabbar gradient indicator
a custom tabbar gradient indicator for flutter, and it support ios and android

## Screenshots

![image](https://github.com/ahyangnb/tabbar_gradient_indicator_plus/blob/main/images/example.jpg?raw=true)
![image2](https://github.com/ahyangnb/tabbar_gradient_indicator_plus/blob/main/images/example2.jpeg?raw=true)


## Update content.
1. support set the direction of gradient.
2. support set the radius of indicator.
3. support set the fixedWidth of indicator.

## Getting Started

1. Depend on it by adding this to your pubspec.yaml file: ```tabbar_gradient_indicator_plus: ^1.0.0```

2. Import it: ```import 'package:tabbar_gradient_indicator_plus/tabbar_gradient_indicator_plus.dart'```

3. set the **indicator** property of Tabbar like this:
````dart
TabBar(indicator: TabBarGradientIndicator(
            gradientColor: [Color(0xff579CFA) , Color(0xff2FDEE7)],
            indicatorWidth: 2)
)
````
