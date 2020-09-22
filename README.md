<div align="center">

## Printers List


</div>

### Description

Get a list of all the printers available on your computer (Locally and networked)
 
### More Info
 
A list of printers


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Anil Upadhyay](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/anil-upadhyay.md)
**Level**          |Intermediate
**User Rating**    |4.0 (24 globes from 6 users)
**Compatibility**  |VB 5\.0, VB 6\.0
**Category**       |[Miscellaneous](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/miscellaneous__1-1.md)
**World**          |[Visual Basic](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/visual-basic.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/anil-upadhyay-printers-list__1-34742/archive/master.zip)





### Source Code

```
'Get all printers available on the computer
'usage
'label1.caption=printeravailable
Public Function printeravailable() As String
Dim p As Printer
    For Each p In Printers
    printeravailable = printeravailable & p.DeviceName & " on " & p.Port & vbCrLf
    Next
End Function
```

