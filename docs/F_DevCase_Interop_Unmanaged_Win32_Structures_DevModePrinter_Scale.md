# DevModePrinter.Scale Field
 

Specifies the factor by which the printed output is to be scaled. 

 The apparent page size is scaled from the physical page size by a factor of dmScale /100. For example, a letter-sized page with a dmScale value of 50 would contain as much data as a page of 17- by 22-inches because the output text and graphics would be half their original height and width.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public short Scale
```

**VB**<br />
``` VB
Public Scale As Short
```

**VB Usage**<br />
``` VB Usage
Dim instance As DevModePrinter
Dim value As Short

value = instance.Scale

instance.Scale = value
```

**C++**<br />
``` C++
public:
short Scale
```

**F#**<br />
``` F#
val mutable Scale: int16
```


#### Field Value
Type: Int16

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Structures_DevModePrinter">DevModePrinter Structure</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Structures">DevCase.Interop.Unmanaged.Win32.Structures Namespace</a><br />