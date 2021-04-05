## Description

When I use the `onLoad` prop in my central `html.js` file it is being removed, while in other files it works as expected.

### Steps to reproduce

Add a html.js file and add an element with onLoad attribute - for example a `<link onLoad="stuff">`

https://github.com/Primajin/gatsby-bug-onload/commit/9658ec939cf7a42787e67f760ce10e599fdb5e0b

![image](https://user-images.githubusercontent.com/1742115/113567791-8ed60a80-960f-11eb-88eb-4c7ccafd471d.png)
![image](https://user-images.githubusercontent.com/1742115/113567818-9a293600-960f-11eb-8f19-6ebb94672a94.png)

### Expected result

The element is rendered with the onLoad attribute.

### Actual result

The element is rendered without the onLoad attribute.

### Environment

```
  System:
    OS: Windows 10 10.0.19042
    CPU: (8) x64 AMD FX-8370 Eight-Core Processor
  Binaries:
    Node: 14.15.3 - C:\Program Files\nodejs\node.EXE
    Yarn: 1.22.10 - ~\AppData\Roaming\npm\yarn.CMD
    npm: 6.14.11 - C:\Program Files\nodejs\npm.CMD
  Languages:
    Python: 3.9.3
  Browsers:
    Chrome: 89.0.4389.114
    Edge: Spartan (44.19041.906.0), Chromium (89.0.774.68), ChromiumDev (--> [posh-monokai] Black       DarkBlue    DarkGreen
DarkCyan    DarkRed     DarkMagenta DarkYellow  Gray
--> [posh-monokai] DarkGray    Blue        Green       Cyan        Red         Magenta     Yellow      White)
  npmPackages:
    gatsby: ^3.2.1 => 3.2.1
```
