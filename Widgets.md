# Widget

Widgets are the central class hierarchy in the Flutter framework. Almost everything in Flutter is widgets. There are two type of basic Widget we can extend our classes: StatefulWidget or StatelessWidget.

## StatefulWidget
StatefulWidget are all the widget that interally have a dynamic value that can change during usage (Mutable). It can receive an input value in the constructor or reference to functions.

## StatelessWidget
StatelessWidget are components that are rendered and keep that value (Immutable). A refresh by a parent is needed to update the content. It can receive a value from the constructor.

| Widget | Description |
| --- | ----------- |
| MaterialApp | An application that uses Material Design. Wraps widgets that are commonly required for Material Design applications. |
| ThemeData | Configuration of the overall visual Theme for a MaterialApp or a widget subtree within the app. |
| Scaffold | Implements the basic Material Design visual layout structure. |
| AppBar | A Material Design app bar consists of a toolbar and potentially other widgets. |
| Text | Displays a string of text with single style. Might break across multiple lines or might all be displayed on the same line depending on the layout constraints.|
| TextStyle | An immutable style describing how to format and paint text. |
| Center | Widget that centers its child within itself. |
| Divider | A thin horizontal line, with padding on either side. Can be used in lists, Drawers, and elsewhere to separate content. |
| ListView | A scrollable list of widgets arranged linearly. Commonly used scrolling widget. |
| ListTile | A single fixed-height row that typically contains some text as well as a leading or trailing icon. Contains 1 to 3 lines of text optionally flanked by icons or other widgets.|
| Column | Displays its children in a vertical array and does not scroll.|
| FloatingActionButton | Circular icon button that hovers over content to promote a primary action in the application. |
| Icon | A graphical icon widget drawn with a glyph o symbol from a font described in an IconData such as material's predefined IconDatas in Icons. |
