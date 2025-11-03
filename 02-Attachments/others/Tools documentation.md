---
title: Tools documentation
tags:
created: 2025-10-28 星期二 22:45
modified: 2025-10-31 星期五 09:13
---
# Templater
[入门视频](https://www.youtube.com/watch?v=91H_0ii4S-A)
[官方文档](https://silentvoid13.github.io/Templater/)


# Excalidraw
## 调色板
1. 怎么配置色板
- 在色盘上选好后，ctrl+shift+i打开开发者工具-console
- 在最底下的光标`>`处输入：
```
s=`source:: [Paletton Palette](${window.location.href})`;
document
  .querySelector(".pane.pane-palette")
  .querySelectorAll("[title]")
  .forEach((x,i)=>{
    s += `\n${x.getAttribute("title")}`;
    if((i+1)%5===0) s+="\n";
  })
console.log(s)
```
- 将获得的代码全都粘贴到`Excalidraw-Palletes-新建文件`中。
- 点击excalidraw里的插件Palette Loader -> Load palette from file ->选中文件。




---
# Back Matter

**Source**
<!-- Always keep a link to the source- --> 
- based_on::

**References**
<!-- Links to pages not referenced in the content. see: [[related note]] because <reason> -->
- see:: 

**Terms**
<!-- Links to definition pages. -->
- 

**Target**
<!-- Link to project note or externaly published content. -->
- used_in::

---
**Tasks**
<!-- What remains to be done with this note? --> 
- 

**Questions**
<!-- What remains for you to consider? --> 
- question::

---
**Template Help**
<!-- Links to external help pages on GitHub. -->
- [Basic Template Structure](https://github.com/groepl/Obsidian-Templates#basic-template-structure)
- [How to Use Links](https://github.com/groepl/Obsidian-Templates#how-to-use-links)
- [How to Use Tags](https://github.com/groepl/Obsidian-Templates#how-to-use-tags)
- [How to Search Notes](https://github.com/groepl/Obsidian-Templates#how-to-search-notes)
- [Plugins Needed](https://github.com/groepl/Obsidian-Templates#obsidian-plugins-needed)
- [Find Latest Updates](https://github.com/groepl/Obsidian-Templates)

