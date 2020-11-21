# NativeUtil.MakeLParam Method (UInt16, UInt16)
 

Creates a lParam value from two UInt16 values. 



**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Tools">DevCase.Interop.Unmanaged.Tools</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static IntPtr MakeLParam(
	ushort loWord,
	ushort hiWord
)
```

**VB**<br />
``` VB
Public Shared Function MakeLParam ( 
	loWord As UShort,
	hiWord As UShort
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim loWord As UShort
Dim hiWord As UShort
Dim returnValue As IntPtr

returnValue = NativeUtil.MakeLParam(loWord, 
	hiWord)
```

**C++**<br />
``` C++
public:
static IntPtr MakeLParam(
	unsigned short loWord, 
	unsigned short hiWord
)
```

**F#**<br />
``` F#
static member MakeLParam : 
        loWord : uint16 * 
        hiWord : uint16 -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>loWord</dt><dd>Type: System.UInt16<br />The low-order WORD.</dd><dt>hiWord</dt><dd>Type: System.UInt16<br />The high-order WORD.</dd></dl>

#### Return Value
Type: IntPtr<br />The resulting lParam value.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-makelparam" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-makelparam</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim lParam as IntPtr = MakeLParam(UShort.MaxValue, UShort.MaxValue)
```


## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Tools_NativeUtil">NativeUtil Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Tools_NativeUtil_MakeLParam">MakeLParam Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Tools">DevCase.Interop.Unmanaged.Tools Namespace</a><br />Message.LParam<br />