---
title: How To Add Assets In A Flutter Project
categories: [Flutter, Tutorial]
tags: [assets, flutter]
---

# Open your Yaml File

First let's look into where you are going to store those assets to begin with. Now the convention around this is that you have a root folder named `assets` in your project. Within that you can add a network of folders to store your assets. Things like: 
1. icons 
2. logo
3. images
4. avatars
5. fonts
6. etc


Scroll all the way to the bottom of the `pubspec.yaml` file

Add the following code

```yaml

assets:
  - /assets/images/bob.png

```

This is one way to include an image into the project.

However it may be useful to you to include multiple assets in one go. In this instance you could include the the images folder. Which means whatever that goes into that folder will automatically be considered by your project. Here's how you do it.

```yaml
assets:
    - /assets/icons/

```


