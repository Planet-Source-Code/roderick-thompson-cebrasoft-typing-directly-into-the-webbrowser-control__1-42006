<div align="center">

## Typing directly into the WebBrowser Control


</div>

### Description

After spending a long time trying to find (there is nothing else on PSC)this code and eventually sourcing it, I thought I would share this with you all! Did you know it is possible to type directly into the WebBrowser control in VB with just 3 lines of code?
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Roderick Thompson, CebraSoft](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/roderick-thompson-cebrasoft.md)
**Level**          |Advanced
**User Rating**    |4.0 (8 globes from 2 users)
**Compatibility**  |VB 6\.0
**Category**       |[Internet/ HTML](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/internet-html__1-34.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/roderick-thompson-cebrasoft-typing-directly-into-the-webbrowser-control__1-42006/archive/master.zip)





### Source Code

```
'INITIALISE THE CONTROL TO A BLANK PAGE
WebBrowser1.Navigate2 "about:blank"
'ENABLED DESIGN MODE
Set doc = WebBrowser1.Document
doc.DesignMode = "On"
```

