You can use materials icons at run time or you can define a material icon name and use icon.

## Features

Dynamic Icons, Use icons with a dynamic string name.

- Use material Icons with icon name only
- Define String from remote and use


## Getting started

For example, say you want to use the icons which you are changing at run time.

In normal way we use icons as
```dart
Icon(Icons.add);
```
which show '+' icon.

Now if you want to define from BE or from APIs then you have to provide a string name like 'add'.
But you can not use String 'add' directly and the reason is Icons are 'DataIcons'.

So for this problem we have introduce a new package as 'dynamic_icons_matte'

To use `dynamic_icons_matte`:

```dart
dependencies:
flutter:
sdk: flutter
dynamic_icons_matte: ^0.0.1

```

To import `dynamic_icons_matte`:

```dart
import 'package:dynamic_icons/dynamic_icons_matte.dart';
```

## Usage

```dart
DynamicIconsMatte(name: 'add',color: Colors.black,sizes: 100,);
```

## Additional information

You can define any material name here, if icons will not exists then this will show 'launch ' icon as default.

Full list of supported icon names:
See icons_list.md