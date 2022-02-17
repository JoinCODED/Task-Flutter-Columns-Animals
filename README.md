# Animal Information 🦊

![result](https://user-images.githubusercontent.com/84308096/154492581-93214499-5aeb-4abd-9fc7-7759e29daa94.png)


Create a new project and design an application similar to the above screenshot.

💡 Hints:

The [Column](https://api.flutter.dev/flutter/widgets/Column-class.html) widget.

The [Image](https://api.flutter.dev/flutter/widgets/Image-class.html) widget.

## Instructions

1. Create a new project call it: animals_flutter_app and set it up like you did in the previous task.
2. Pick up an animal picture online and create a folder in your root file and call it `assets`.
3. And inside that folder create another folder named `images`.
4. Drag your image inside this folder.
5. Open `pubspec.yaml` and add your image path:

```yaml
assets:
  - assets/images/animal.png
```

⚠️ Make sure of your image name and type, maybe rename your image to `animal` and check the type ex: jpg, png, jpeg etc.

6. In your `Scaffold` `body` argument, pass it a `Column` widget.
7. In your `Column`s `children` argument, add an `Image.asset` widget.
8. Give your image a `height` and `width`.
9. Add 3 `Text` widgets and fill them up with the name, age and gender.
10. Add a `mainAxisAlignment` and `crossAxisAlignment` arguments to your `Column` widget.
11. Wrap your `Image` widget with a `Container` widget.
12. Give it an `Alignment` argument.
13. Wrap each `Text` widget with a `Container` widget.
14. Give your first `Text` widget a margin from the `top` and from the `left`.
15. Give the rest `Text` widgets a margin from the `left`.

### 🍋 The basic challenge title

1. Give your each container a different color, and maybe style your text more 🖌️.

### 🌶 The Extreme challenge title

1. Add a `Row` widget so the the 3 `Text` widgets appears on one line.

💡 Hints:
The [Row](https://api.flutter.dev/flutter/widgets/Row-class.html) widget.
