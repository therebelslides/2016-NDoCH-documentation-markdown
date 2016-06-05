---

# Markdown & Documentation

# c4sf.me/markdown

---

A handy Mac OS Markdown editor: [Muo](http://25.io/mou/)

### Markdown Basics

# h1 Heading 8-)
## h2 Heading
### h3 Heading
#### h4 Heading
##### h5 Heading
###### h6 Heading


## Horizontal Rules

___

---

***


## Emphasis

**This is bold text**

__This is bold text__

*This is italic text*

_This is italic text_

~~Strikethrough~~


## Blockquotes


> Blockquotes can also be nested...
>> ...by using additional greater-than signs right next to each other...
> > > ...or with spaces between arrows.


## Lists

Unordered

+ Create a list by starting a line with `+`, `-`, or `*`
+ Sub-lists are made by indenting 2 spaces:
  - Marker character change forces new list start:
    * Ac tristique libero volutpat at
    + Facilisis in pretium nisl aliquet
    - Nulla volutpat aliquam velit
+ Very easy!

Ordered

1. Lorem ipsum dolor sit amet
2. Consectetur adipiscing elit
3. Integer molestie lorem at massa


1. You can use sequential numbers...
1. ...or keep all the numbers as `1.`

Start numbering with offset:

57. foo
1. bar


## Code

Inline `code`

Indented code

    // Some comments
    line 1 of code
    line 2 of code
    line 3 of code


Block code "fences"

```
Sample text here...
```

Syntax highlighting

``` js
var foo = function (bar) {
  return bar++;
};

console.log(foo(5));
```

## Tables

| Option | Description |
| ------ | ----------- |
| data   | path to data files to supply the data that will be passed into templates. |
| engine | engine to be used for processing templates. Handlebars is the default. |
| ext    | extension to be used for dest files. |

Right aligned columns

| Option | Description |
| ------:| -----------:|
| data   | path to data files to supply the data that will be passed into templates. |
| engine | engine to be used for processing templates. Handlebars is the default. |
| ext    | extension to be used for dest files. |


## Links

[link text](http://dev.nodeca.com)

[link with title](http://nodeca.github.io/pica/demo/ "title text!")

Autoconverted link https://github.com/nodeca/pica (enable linkify to see)

On Github, you can also link to headers in the same document using `#`

[Blockquotes](#blockquotes)

`[Blockquotes](#blockquotes)`


## Images

![Cat](http://placekitten.com/g/200/300)
![Another cat](http://placekitten.com/g/300/300 "The other cat")

Like links, Images also have a footnote style syntax

`![Alt text][id]`

With a reference later in the document defining the URL location:

`[id]: https://octodex.github.com/images/dojocat.jpg  "The Dojocat"`


![](https://i.imgur.com/K8AnUXo.png)

---

# Documentation

---

#### README

`README` files should contain a few key parts:

- name of the project
- short description
- background / problem statement / solution
- installation / deployment
- usage
- troubleshooting / FAQs
- additional resources / assets
- links to any other supporting docs.

#### Spicing it up!
##### Screenshots!

On Mac, there are some special hotkeys you can use to take screenshots:

| Key Combo | Type | Example |
| --- | --- | --- |
| `Cmd-Shift-3 (⌘-⇧-3)` | Capture entire Screen | ![](https://i.imgur.com/6LIwB4s.jpg) |
| `Cmd-Ctrl-Shift-3 (⌘-Ctrl-⇧-3)` | Capture entire Screen + Add to clipboard | ![](https://i.imgur.com/6LIwB4s.jpg) |
| `Cmd-Shift-4 (⌘-⇧-4)` | Capture portion of Screen | ![](https://i.imgur.com/7HyV9zB.png) |
| `Cmd-Ctrl-Shift-4 (⌘-Ctrl-⇧-4)` | Capture portion of Screen + Add to clipboard | ![](https://i.imgur.com/7HyV9zB.png) |
| `Cmd-Shift-4-Spacebar (﻿⌘-⇧-4-Space)`| Capture entire window (adds window shadow) | ![](https://i.imgur.com/u8Jklwt.png) | 
| `Cmd-Ctrl-Shift-4-Spacebar (﻿⌘-Ctrl-⇧-4-Space)`| Capture entire window (adds window shadow) + Adds to clipboard | ![](https://i.imgur.com/u8Jklwt.png) | 

These will automatically be saved on your Desktop. To change the default location, run the following command in your terminal:

```

defaults write com.apple.screencapture location /Users/username/Pictures/screenshots/;killall SystemUIServer
```

where `/Users/username/Pictures/screenshots/` is the path of the folder where you want your screenshots to be saved.

As Github documentation requires a url for embedding images, uploading the image to an image host (like [imgur](https://imgur.com)) is helpful. There are tools available for auto upload of those screenshots to Imgur:

[![](https://i.imgur.com/HzYOMOn.png)](https://github.com/mileswd/mac2imgur)

##### Animated Gifs!

You can embed animated gifs into your documentation as well! Doing so can add character:

![](http://assets0.ordienetworks.com/images/GifGuide/dancing/tumblr_lhjxn17LeK1qdy7bo.gif)

or valuable walkthrough documentation:

![Imgur](http://i.imgur.com/YWaZgN5.gif)

![Imgur](http://i.imgur.com/an38LZZ.gif)

Recording animated screenshots is really easy, on Windows/Mac OS X, you can use [LICEcap](http://www.cockos.com/licecap/), which is a free animated gif screen recorder.

![](https://i.imgur.com/K8AnUXo.png)
