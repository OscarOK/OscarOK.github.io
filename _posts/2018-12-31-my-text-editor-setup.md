---
layout: article
title: My Text Editor Setup
mode: immersive
header:
  theme: dark
article_header:
  type: overlay
  theme: dark
  background_color: '#203028'
  background_image:
    gradient: 'linear-gradient(160deg, rgba(144,176,97,.5), rgba(41,45,52,.5))'
    src: /assets/images/2018-12-31-my-text-editor-setup/cover.png
---

I use ***Atom*** as my text editor, so let me show you my selection of themes and packages, including settings that I prefer to use.

<!-- Introduction -->
I'm sure a lot of you already know or even have used Atom. But just in case Atom is developed by _GitHub_ so a lot of the community support this project by making packages and themes; this way the editor becomes more _versatile_ for a different type of people's needs. It actually claims to be:

> “The hackable text editor for the 21st Century”.

If you are interested, you can go to the official [website][1] and learn more about it.

Now that we know what is Atom. I need to define the use that I will give to it. My needs are:
- Web development
- Quick code writing for:
    - Python
    - JavaScript
    - C++
- Markdown writing.

With this in mind, I selected some packages that will help me to make the text editor of my dreams.

Let's start, shall we?

<!-- Main body -->
## Editor Settings
For the next steps you may go to the Settings tab, for that just use `Ctrl + ,` or go to the `File -> Settings` menu.

### Tab Length
This is the _number of spaces_ to represent a tab, for my personal likeness I will change it to ***4***.

### Scroll Past End
This simple setting allows the editor to scroll past the end of the last line of the document. This makes more _comfortable_ the reading and working process, let me show you the difference.

<div class="card card--center" style="width:70%">
  <div class="card__image">
    <img class="image" src="/assets/images/2018-12-31-my-text-editor-setup/off-on-scroll-past-end.png"/>
    <div class="overlay overlay--bottom">
      <p>OFF/ON Scroll Past End</p>
    </div>
  </div>
</div>

### Show Indent Guide
Basically show the indentation of the file, which allows me to recognize faster the code structure, perhaps a Python code.

<div class="card card--center" style="width:70%">
  <div class="card__image">
    <img class="image" src="/assets/images/2018-12-31-my-text-editor-setup/off-on-indent-guide.png"/>
    <div class="overlay overlay--bottom">
      <p>OFF/ON Indent Guide</p>
    </div>
  </div>
</div>

### Font Family & Font Size
I just start using ***Fira Code*** font with a size of ***16***, and it turns out beautifully good. The main reason for keeping this font is the pretty way that represents characters or sets of characters.

![Fira Code][fira_code]{:.rounded.shadow.image--center.image--xl}

If you want to see more and learn how to use it visit their [website][2].

## Appearance
Atom's style can be divided between the _theme_ and the _syntax_; being the first one the appearance of the user interface, and the other one the editor appearance, such as text style and colors. To make changes, you may go to settings by `Ctrl + ,` or `File -> Settings` then open the themes section.

### Theme
For the theme, the selection is pretty simple. I use ***One Dark*** which is included with Atom, you only need to select from the _UI Themes_ list.

![One Dark Theme][theme]{:.rounded.shadow.image--center.image--xxl}

### Syntax
The syntax that I use is ***Dracula***, which isn't installed with Atom. We need to search it in the Install section with the theme option, this way we added to the editor. And finally, select it in the _Syntax Theme_ list in the Theme section.

![Dracula Syntax][syntax]{:.rounded.shadow.image--center.image--xxl}

## Packages
The core of this post, the _packages_. This allows us to make improvements to the editor, adding essential functionality that works for our needs.
To install a package, we must open the install section which is in settings.

### Tree
This is already installed. But I made a personal change in its configuration turning on the ***Hide VCS Ignored Files*** option.

### Emmet
Is a popular package that _improves_ HTML & CSS workflow. It allows you to use abbreviation while you are coding providing better performance. Look up their [website][3] for more info.

### Linter
Is a tool used to _analyze_ your code and find errors and warnings. Check out the complete list of supported languages on their [website][4].

### Atom Beautify
Is a really cool [package][5] that allows us to _reformat and clean_ the current code with a simple shortcut. This makes the file or selected text more readable, saving us a lot of time working with bad looking code.

![Atom Beautify Package][atom_beautify]{:.rounded.shadow.image--center.image--xxl}

### Color Picker
As simple as it sounds. I just a [tool][6] that allows us to select a color with the typically RGB color selector. It also shows the selected color in different color models, such as RGB, HEX, and a few more.

![Color Picker Package][color_picker]{:.rounded.shadow.image--center.image--xxl}

### File Icons
Plenty self-explanatory. Add to atom [icons][7] to represent types of files.
So, while you work, you can find files more easily.

![File Icons Package][file_icons]{:.rounded.shadow.image--center.image--xxl}

### Minimap
Provided us a [preview][8] of the full source code.

![MiniMap Package][minimap]{:.rounded.shadow.image--center.image--xxl}

### Pigments
It’s a useful [package][9] to deal with colors in CSS and HTML, displaying the color in the editor.
Just change the marker type to ***Native Dot***, this makes it prettier.

![Pigments Package][pigments]{:.rounded.shadow.image--center.image--xxl}

### Script
With this [package][10], we can _run_ scripts based on file name, a selection of code, or by line number in the editor.

![Script Package][script]{:.rounded.shadow.image--center.image--xxl}

---

<!-- End of the post -->
Well, this is the way I set up my text editor. Now with this, I will remember all the steps to have the perfect text editor for me. I hope this was helpful for anyone out there.

<!-- Links -->
[1]: https://atom.io/
[2]: https://github.com/tonsky/FiraCode
[3]: https://emmet.io/
[4]: https://atomlinter.github.io/
[5]: https://atom.io/packages/atom-beautify
[6]: https://atom.io/packages/color-picker
[7]: https://atom.io/packages/file-icons
[8]: https://atom.io/packages/minimap
[9]: https://atom.io/packages/pigments
[10]: https://atom.io/packages/script

<!-- Image references -->
[fira_code]: /assets/images/2018-12-31-my-text-editor-setup/fira-code.png
[theme]: /assets/images/2018-12-31-my-text-editor-setup/theme.png
[syntax]: /assets/images/2018-12-31-my-text-editor-setup/syntax.png
[atom_beautify]: /assets/images/2018-12-31-my-text-editor-setup/before-after-beautify.png
[color_picker]: /assets/images/2018-12-31-my-text-editor-setup/color-picker.png
[file_icons]: /assets/images/2018-12-31-my-text-editor-setup/file-icons.png
[minimap]: /assets/images/2018-12-31-my-text-editor-setup/minimap.png
[pigments]: /assets/images/2018-12-31-my-text-editor-setup/pigments.png
[script]: /assets/images/2018-12-31-my-text-editor-setup/script.png
