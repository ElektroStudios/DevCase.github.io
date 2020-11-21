# NativeMethods.GetDeviceCaps Method (IntPtr, Int32)
 

Retrieves device-specific information for the specified device.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("GDI32.dll", CharSet = CharSet.Auto, ExactSpelling = true, 
	SetLastError = true)]
public static int GetDeviceCaps(
	IntPtr hdc,
	int index
)
```

**VB**<br />
``` VB
<DllImportAttribute("GDI32.dll", CharSet := CharSet.Auto, ExactSpelling := true, 
	SetLastError := true>]
Public Shared Function GetDeviceCaps ( 
	hdc As IntPtr,
	index As Integer
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim hdc As IntPtr
Dim index As Integer
Dim returnValue As Integer

returnValue = NativeMethods.GetDeviceCaps(hdc, 
	index)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"GDI32.dll", CharSet = CharSet::Auto, ExactSpelling = true, 
	SetLastError = true)]
static int GetDeviceCaps(
	IntPtr hdc, 
	int index
)
```

**F#**<br />
``` F#
[<DllImportAttribute("GDI32.dll", CharSet = CharSet.Auto, ExactSpelling = true, 
	SetLastError = true)>]
static member GetDeviceCaps : 
        hdc : IntPtr * 
        index : int -> int 

```


#### Parameters
&nbsp;<dl><dt>hdc</dt><dd>Type: System.IntPtr<br />A handle To a DC (Device Context).</dd><dt>index</dt><dd>Type: System.Int32<br />The item to be returned.</dd></dl>

#### Return Value
Type: Int32<br />The return value specifies the value of the desired item.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/dd144877%28VS.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/dd144877%28VS.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetDeviceCaps">GetDeviceCaps Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />