# Vim Hands-On Tutorial Workshop

![GitHub Repo stars](https://img.shields.io/github/stars/dofy/learn-vim)  
![GitHub](https://img.shields.io/github/license/dofy/learn-vim)  
![GitHub contributors](https://img.shields.io/github/contributors/dofy/learn-vim)  
![GitHub commit activity (branch)](https://img.shields.io/github/commit-activity/m/dofy/learn-vim)  

[View Chapters](chapters/README.md)

---

## Workshop Overview

Learning Vim can be challenging by just reading documentation or watching videos. The best way to master Vim is through **hands-on experience** in realistic scenarios.

This workshop uses Markdown-based files that serve dual purposes:

1. **Instructional reading material**
2. **Interactive exercises in Vim**

You can read the files normally, or open them in Vim to practice commands in real time (recommended).

---

## How to Use

1. Clone the repository:

```bash
git clone https://github.com/your-org/your-vim-workshop.git
```

2. Navigate to the content folder:
```bash
  cd learn-vim/chapters
```

3. Open a chapter in Vim:
```bash
vim chapter01.md
```



## Formatting Rules

```Markdown

## Major titles represent a large category

### Subtitles represent subcategories under this major category

Text without any formatting is a normal description for reading purposes only.

> The text embedded in the quoted block is an instruction to operate, and you
> can follow what is mentioned in it
>
> Also operators or commands are included in symbols like `:w`.

The < and > in commands such as f<X> do not need to be typed, <X> represents a
variable, i.e. you can type fa or fb or fC

_Note: Commands are case-sensitive (matters requiring attention appear in
symbols such as the current line)_

```

> [!NOTE]
>
> If you already have your own `.vimrc` file (refer to
> [Chapter 4](chapters/chapter04.md)) and have changed some of the defaults in it, it
> may cause some operations to not match the tutorial. In this case, you can run
> `Vim` with the following command:
>
> ```bash
> # Do not load the configuration file
> vim -u NONE
> # Load a specific configuration file
> vim -u <filename>
> ```

## Index

### Basic operations

1. [Chapter 1: Cursor Movement](chapters/chapter01.md)
1. [Chapter 2: Opening Files, Finding Content](chapters/chapter02.md)
1. [Chapter 3: Modify and Save Documents](chapters/chapter03.md)
1. [Chapter 4: Some Tips](chapters/chapter04.md)
1. [Chapter 5: Split Screen and Tabs](chapters/chapter05.md)
1. [Chapter 6: Block Operations](chapters/chapter06.md)
1. [Chapter 7: Macros in Vim](chapters/chapter07.md)

### Additional content

1. [Vim Modes](chapters/vim-modes.md)
1. [Vim plugins](chapters/plugin.md)
1. [Plugin Recommendations](chapters/plugins/index.md)
   1. [NERDTree](chapters/plugins/nerdtree.md)
   1. [EasyAlign](chapters/plugins/easyalign.md)
   1. [Airline & Themes](chapters/plugins/airline.md)
   1. [surround.vim](chapters/plugins/surround.md)

> [!NOTE]
>
> - In the tutorials, you can navigate to the next chapter or related chapters,
>   and locate the file name to open it by executing `gf` (goto file). Related
>   files
> - You can always open the relevant chapter to view, and then use `:bp` to go
>   back to the previous file (this command will (This command is covered in
>   [Chapter 2](chapters/chapter02.md)).
> - You may get a file not saved error when you exit the tutorial with `:q` or
>   `:qa`, try adding `!` to the end of the command!

## Recommend a few Vim configurations

- [dofy / **7th-vim**][7th-vim]
- [kepbod / **ivim**][kepbod]
- [chxuan / **vimplus**][chxuan]
- [SpaceVim / **SpaceVim**][spacevim]

## Recommends a couple of other excellent Vim tutorials

- Run `vimtutor` on the console. This is the official hands-on tutorial for Vim.
- [Concise Vim Practice Tips][coolshell] Great tutorial to get started!
- [Vim Galore][vimgalore] Frequently updated, a must-read for Vim.
- [Daily Vim][liuzhijun] 30 articles, the content is more complete!
- [A book for learning the Vim editor][learnvim] Another Learn Vim (English)
- [Open Vim][openvim] Interactive Vim Tutorials
- [QuickRef.ME/vim][quickref] Vim cheatsheet

## Cheatsheets

> [Vim Cheat Sheet][cheatsheets1]

> [A Great Vim Cheat Sheet][cheatsheets2]

> [![003][cheatsheets3]][cheatsheets3]

> [![004][cheatsheets4]][cheatsheets4]

> [![005][cheatsheets5]][cheatsheets5]

**Thanks again for your interest! If you love, please share. Love life, love
VIM!**

[7th-vim]: https://github.com/dofy/7th-vim
[kepbod]: https://github.com/kepbod/ivim
[chxuan]: https://github.com/chxuan/vimplus
[spacevim]: https://github.com/SpaceVim/SpaceVim
[coolshell]: http://coolshell.cn/articles/5426.html
[vimgalore]: https://github.com/mhinz/vim-galore
[liuzhijun]: http://liuzhijun.iteye.com/category/270228
[learnvim]: https://github.com/iggredible/Learn-Vim
[openvim]: https://openvim.com/
[quickref]: https://quickref.me/vim
[cheatsheets1]: https://vim.rtorr.com/lang/zh_tw
[cheatsheets2]: https://vimsheet.com/
[cheatsheets3]: https://people.csail.mit.edu/vgod/vim/vim-cheat-sheet-en.png



