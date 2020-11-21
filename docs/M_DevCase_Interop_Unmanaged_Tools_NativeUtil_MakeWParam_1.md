# NativeUtil.MakeWParam Method (UInt16, UInt16)
 

Creates a wParam value from two UInt16 values. 



**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Tools">DevCase.Interop.Unmanaged.Tools</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static IntPtr MakeWParam(
	ushort loWord,
	ushort hiWord
)
```

**VB**<br />
``` VB
Public Shared Function MakeWParam ( 
	loWord As UShort,
	hiWord As UShort
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim loWord As UShort
Dim hiWord As UShort
Dim returnValue As IntPtr

returnValue = NativeUtil.MakeWParam(loWord, 
	hiWord)
```

**C++**<br />
``` C++
public:
static IntPtr MakeWParam(
	unsigned short loWord, 
	unsigned short hiWord
)
```

**F#**<br />
``` F#
static member MakeWParam : 
        loWord : uint16 * 
        hiWord : uint16 -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>loWord</dt><dd>Type: System.UInt16<br />The low-order WORD.</dd><dt>hiWord</dt><dd>Type: System.UInt16<br />The high-order WORD.</dd></dl>

#### Return Value
Type: IntPtr<br />The resulting wParam value.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-makewparam" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-makewparam</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim wParam as IntPtr = MakeWParam(UShort.MaxValue, UShort.MaxValue)
```


## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Tools_NativeUtil">NativeUtil Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Tools_NativeUtil_MakeWParam">MakeWParam Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Tools">DevCase.Interop.Unmanaged.Tools Namespace</a><br />Message.WParam<br />