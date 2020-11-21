# NativeUtil.MakeWParam Method (Int32, Int32)
 

Creates a wParam value from two Int32 values. 

 You must call this method overload if you need to use negative values. 



**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Tools">DevCase.Interop.Unmanaged.Tools</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static IntPtr MakeWParam(
	int lo,
	int hi
)
```

**VB**<br />
``` VB
Public Shared Function MakeWParam ( 
	lo As Integer,
	hi As Integer
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim lo As Integer
Dim hi As Integer
Dim returnValue As IntPtr

returnValue = NativeUtil.MakeWParam(lo, 
	hi)
```

**C++**<br />
``` C++
public:
static IntPtr MakeWParam(
	int lo, 
	int hi
)
```

**F#**<br />
``` F#
static member MakeWParam : 
        lo : int * 
        hi : int -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>lo</dt><dd>Type: System.Int32<br />The low-order Int32 value.</dd><dt>hi</dt><dd>Type: System.Int32<br />The high-order Int32 value.</dd></dl>

#### Return Value
Type: IntPtr<br />The resulting wParam value.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-makewparam" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-makewparam</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim wParam as IntPtr = MakeWParam(Integer.MaxValue, Integer.MaxValue)
```


## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Tools_NativeUtil">NativeUtil Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Tools_NativeUtil_MakeWParam">MakeWParam Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Tools">DevCase.Interop.Unmanaged.Tools Namespace</a><br />Message.WParam<br />