# NativeMethods.SelectObject Method (IntPtr, IntPtr)
 

Selects an object into a specified device context. 

 The new object replaces the previous object of the same type.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("GDI32.dll", CharSet = CharSet.Auto)]
public static IntPtr SelectObject(
	IntPtr hdc,
	IntPtr hObject
)
```

**VB**<br />
``` VB
<DllImportAttribute("GDI32.dll", CharSet := CharSet.Auto>]
Public Shared Function SelectObject ( 
	hdc As IntPtr,
	hObject As IntPtr
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim hdc As IntPtr
Dim hObject As IntPtr
Dim returnValue As IntPtr

returnValue = NativeMethods.SelectObject(hdc, 
	hObject)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"GDI32.dll", CharSet = CharSet::Auto)]
static IntPtr SelectObject(
	IntPtr hdc, 
	IntPtr hObject
)
```

**F#**<br />
``` F#
[<DllImportAttribute("GDI32.dll", CharSet = CharSet.Auto)>]
static member SelectObject : 
        hdc : IntPtr * 
        hObject : IntPtr -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>hdc</dt><dd>Type: System.IntPtr<br />A handle to the Device Context (DC).</dd><dt>hObject</dt><dd>Type: System.IntPtr<br />A handle to the object to be selected.</dd></dl>

#### Return Value
Type: IntPtr<br />If the selected object is not a region and the function succeeds, the return value is a handle to the object being replaced. 

 If the selected object is a region and the function succeeds, the return value is one of the following values.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/dd162957%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/dd162957%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_SelectObject">SelectObject Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />