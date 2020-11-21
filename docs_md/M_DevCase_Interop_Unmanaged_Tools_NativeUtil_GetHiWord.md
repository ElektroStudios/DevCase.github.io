# NativeUtil.GetHiWord Method (IntPtr)
 

Gets the high-order WORD of a DWORD value.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Tools">DevCase.Interop.Unmanaged.Tools</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static ushort GetHiWord(
	IntPtr dWord
)
```

**VB**<br />
``` VB
Public Shared Function GetHiWord ( 
	dWord As IntPtr
) As UShort
```

**VB Usage**<br />
``` VB Usage
Dim dWord As IntPtr
Dim returnValue As UShort

returnValue = NativeUtil.GetHiWord(dWord)
```

**C++**<br />
``` C++
public:
static unsigned short GetHiWord(
	IntPtr dWord
)
```

**F#**<br />
``` F#
static member GetHiWord : 
        dWord : IntPtr -> uint16 

```


#### Parameters
&nbsp;<dl><dt>dWord</dt><dd>Type: System.IntPtr<br />The DWORD value that contains the LOWORD and the HIWORD.</dd></dl>

#### Return Value
Type: UInt16<br />The high-order WORD value.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim value as UShort = GetHiWord(UInteger.MaxValue)
```


## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Tools_NativeUtil">NativeUtil Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Tools_NativeUtil_GetHiWord">GetHiWord Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Tools">DevCase.Interop.Unmanaged.Tools Namespace</a><br />