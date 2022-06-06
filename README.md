<!-- just a suggestion, wouldn't be nicer if we change the title to "animal profile"?  -->
# Animal Information 🦊 
![result](https://user-images.githubusercontent.com/84308096/154492581-93214499-5aeb-4abd-9fc7-7759e29daa94.png)


Create a new app and design it similar to the screenshot above.

💡 Hints:

The [Column](https://api.flutter.dev/flutter/widgets/Column-class.html) widget.

The [Image](https://api.flutter.dev/flutter/widgets/Image-class.html) widget.

The [Container](https://api.flutter.dev/flutter/widgets/Container-class.html) widget.

## 🍋 Instructions

1. Create a new project call it: animals_flutter_app and set it up like what you did in the previous task.
2. Create a folder in the root of the project and call it `assets`.
3. Inside the `assets` folder, create another folder named `images`.
4. Pick an animal picture of your choice and drag it into the `images` folder.
5. Open the `pubspec.yaml` file and add your image path:

```yaml
assets:
  - assets/images/<YOUR_IMAGE_NAME>.png
```

⚠️ Make sure of your image name and type. You can rename your image to something easy to remember like "animal", then check its type ex: jpg, png, jpeg, etc.

6. Pass a `Column` widget to the `body` argument in the `Scaffold`.
7. Pass an `Image.asset` widget to the `Column`s `children` argument, then pass the image's path to the `Image.asset` widget.
8. Give your image a `height` and `width`.
9. Pass three `Text` widgets to the `Column`s `children` argument just below the `Image.asset` widget, and fill them up with the name, age and gender.
10. Add a `mainAxisAlignment` and `crossAxisAlignment` arguments to the `Column` widget.
11. Wrap the `Image` widget with a `Container` widget.
12. Give the `Container` widget an `alignment` argument.
13. Wrap each `Text` widget with a `Container` widget.
14. Give the first `Text`'s `Container` widget a margin from the `top` and `left`.
15. Give the rest of `Text` widgets a margin from the `left`.

### 🤼‍♂️ Decoration

1. Give each `Container` a different color, and maybe style the text better🖌️.

### 🌶 Bonus

1. Use the `Row` widget to make the three `Text` widgets appear on one line.
2. Make the animal image circular.  

💡 Hints:
The [Row](https://api.flutter.dev/flutter/widgets/Row-class.html) widget.
