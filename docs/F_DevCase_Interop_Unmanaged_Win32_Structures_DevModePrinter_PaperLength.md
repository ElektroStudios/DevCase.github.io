# DevModePrinter.PaperLength Field
 

For printer devices only, overrides the length of the paper specified by the <a href="F_DevCase_Interop_Unmanaged_Win32_Structures_DevModePrinter_PaperSize">PaperSize</a> member, either for custom paper sizes or for devices such as dot-matrix printers that can print on a page of arbitrary length. 

 These values, along with all other values in this structure that specify a physical length, are in tenths of a millimeter.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public short PaperLength
```

**VB**<br />
``` VB
Public PaperLength As Short
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevModePrinter
Dim value As Short

value = instance.PaperLength

instance.PaperLength = value
```

**C++**<br />
``` C++
public:
short PaperLength
```

**F#**<br />
``` F#
val mutable PaperLength: int16
```


#### Field Value
Type: Int16

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_DevModePrinter">DevModePrinter Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />