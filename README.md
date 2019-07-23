# Flutter Stack Card

Stack Card Widget is fastest way to create swap card in flutter.

## Screenshots

![StackType.middle](example/assets/screenshots/middle.png?raw=true "StackType.middle")
![StackType.right](example/assets/screenshots/right.png?raw=true "StackType.right")

## Usage

```dart
StackCard.builder(
    itemCount: /* Item Count */,
    displayIndicator: /* Flag to display the indicator */,
    displayIndicatorBuilder: /* Customize the indicator */,
    onSwap: (index) {
        /* listen for swapping */
    },
    itemBuilder: (context, index) {
        /* item builder */
    }
)
```

## Example

Please find example in here: [Example](example/lib/main.dart)
