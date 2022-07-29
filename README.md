# Animal Information 🦊

![result](https://user-images.githubusercontent.com/84308096/154492581-93214499-5aeb-4abd-9fc7-7759e29daa94.png)

Create a new project and design an application similar to the above screenshot.

## Setup

1. Create a new Github repo
2. Create a local repo using the command `git init`
3. Push to the new repo

```shell
git remote add origin https://github.com/YourUsername/repoName.git
```

```shell
git branch -M main
```

```shell
git push -u origin main
```

## 🍋 Instructions

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

💡 Here's the widgets you will need:

The [Column](https://api.flutter.dev/flutter/widgets/Column-class.html) widget.

The [Image](https://api.flutter.dev/flutter/widgets/Image-class.html) widget.

The [Container](https://api.flutter.dev/flutter/widgets/Container-class.html) widget.

The [Text](https://api.flutter.dev/flutter/widgets/Text-class.html) widget.

### 🤼‍♂️ Decoration

1. Give your each container a different color, and maybe style your text more 🖌️.

### 🌶 Bonus

1. Add a `Row` widget so the the 3 `Text` widgets appears on one line.
2. Make the animal image circular .

💡 Hints:
The [Row](https://api.flutter.dev/flutter/widgets/Row-class.html) widget.

## Push to Github

```shell
git add .
```

```shell
git commit -m "your message"
```

```shell
git push
```
