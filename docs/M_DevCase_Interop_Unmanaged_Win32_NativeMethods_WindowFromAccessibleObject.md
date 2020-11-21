# NativeMethods.WindowFromAccessibleObject Method 
 

Retrieves the window handle that corresponds to a particular instance of an IAccessible interface.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("OleAcc.dll", SetLastError = true)]
public static HResult WindowFromAccessibleObject(
	IAccessible acc,
	ref IntPtr refHwnd
)
```

**VB**<br />
``` VB
<DllImportAttribute("OleAcc.dll", SetLastError := true>]
Public Shared Function WindowFromAccessibleObject ( 
	acc As IAccessible,
	ByRef refHwnd As IntPtr
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim acc As IAccessible
Dim refHwnd As IntPtr
Dim returnValue As HResult

returnValue = NativeMethods.WindowFromAccessibleObject(acc, 
	refHwnd)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"OleAcc.dll", SetLastError = true)]
static HResult WindowFromAccessibleObject(
	IAccessible^ acc, 
	IntPtr% refHwnd
)
```

**F#**<br />
``` F#
[<DllImportAttribute("OleAcc.dll", SetLastError = true)>]
static member WindowFromAccessibleObject : 
        acc : IAccessible * 
        refHwnd : IntPtr byref -> HResult 

```


#### Parameters
&nbsp;<dl><dt>acc</dt><dd>Type: Accessibility.IAccessible<br />Pointer to the IAccessible interface whose corresponding window handle will be retrieved. 

 This parameter must not be a null reference (`Nothing` in Visual Basic).</dd><dt>refHwnd</dt><dd>Type: System.IntPtr<br />Address of a variable that receives a handle to the window containing the object specified in *acc* parameter. 

 If this value is Zero after the call, the object is not contained within a window; for example, the mouse pointer is not contained within a window.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />If the function succeeds, the return value is <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. 

 If the function fails, the return value is a different <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> value.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/oleacc/nf-oleacc-windowfromaccessibleobject" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/oleacc/nf-oleacc-windowfromaccessibleobject</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />