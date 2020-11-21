# DevModePrinter.PaperSize Field
 

For printer devices only, selects the size of the paper to print on. 

 This member can be set to zero if the length and width of the paper are both set by the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_DevModePrinter_PaperLength">PaperLength</a> and <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_DevModePrinter_PaperWidth">PaperWidth</a> members. 

 Otherwise, the PaperSize member can be set to a device specific value greater than or equal to `DMPAPER_USER`.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public short PaperSize
```

**VB**<br />
``` VB
Public PaperSize As Short
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevModePrinter
Dim value As Short

value = instance.PaperSize

instance.PaperSize = value
```

**C++**<br />
``` C++
public:
short PaperSize
```

**F#**<br />
``` F#
val mutable PaperSize: int16
```


#### Field Value
Type: Int16

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_DevModePrinter">DevModePrinter Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />