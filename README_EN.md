## Description

Language：English | [中文](https://github.com/deemoprobe/hugo-papermod2#%E8%AF%B4%E6%98%8E)

> Hugo PaperMod2 is a theme based on [Hugo PaperMod](https://github.com/adityatelange/hugo-PaperMod).

## 1. Git clone pull code

① Use `git clone` to pull the code to the desktop. At this time, the hugo-papermod2 directory will be generated on the desktop

② Enter the hugo-papermod2 directory and enter `git submodule update --init` to pull the submodule under themes / Hugo papermod / and put the official theme inside

## 2. Startup interface

③ Return the directory to hugo-papermod2, enter `hugo server -d` in the terminal, and enter: localhost:1313 in the browser to see the ready-made blog template.

## 3. Modify information

There are many personal information in the template that need to be configured by yourself. Please be patient to modify it. You can refer to the blogger's website building tutorial:[https://YOUR_DOMAIN/posts/blog/](https://YOUR_DOMAIN/posts/blog/)

## 4. Hugo blog exchange group

🎉🎉 YOUR_QQ 🎉🎉

## 5. How to use shortcodes

`bilibili: {{< bilibili BV1Fh411e7ZH(填 bvid) >}}`

`youtube: {{< youtube w7Ft2ymGmfc >}}`

`ppt: {{< ppt src="网址" >}}`

`douban: {{< douban src="网址" >}}`

```bash
#Intra article link card
#To add md at the end, you can only fill in the relative path, as shown below
{{< innerlink src="posts/tech/mysql_1.md" >}}
```

```bash
gallery:

{{< gallery >}}
{{< figure src="https://YOUR_DOMAIN/posts/read/structural_thinking/0.png" >}}
{{< figure src="https://YOUR_DOMAIN/posts/read/structural_thinking/0.png" >}}
{{< /gallery >}}
```

## 5. Possible problems

1. Some users will deploy to GitHub and may encounter cross system problems, such as the prompt `lf will be replaced by CRLF in *******`, and then enter the command: `git config core.autocrlf false`, which solves the problem of automatic conversion of line breaks。
