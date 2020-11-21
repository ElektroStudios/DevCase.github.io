# NativeMethods.CreateStdAccessibleObject Method 
 

Creates an accessible object with the methods and properties of the specified type of system-provided user interface element.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("OleAcc.dll")]
public static HResult CreateStdAccessibleObject(
	IntPtr hWnd,
	int idObject,
	ref Guid refIid,
	out Object refObj
)
```

**VB**<br />
``` VB
<DllImportAttribute("OleAcc.dll">]
Public Shared Function CreateStdAccessibleObject ( 
	hWnd As IntPtr,
	idObject As Integer,
	ByRef refIid As Guid,
	<OutAttribute> ByRef refObj As Object
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As IntPtr
Dim idObject As Integer
Dim refIid As Guid
Dim refObj As Object
Dim returnValue As HResult

returnValue = NativeMethods.CreateStdAccessibleObject(hWnd, 
	idObject, refIid, refObj)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"OleAcc.dll")]
static HResult CreateStdAccessibleObject(
	IntPtr hWnd, 
	int idObject, 
	Guid% refIid, 
	[OutAttribute] Object^% refObj
)
```

**F#**<br />
``` F#
[<DllImportAttribute("OleAcc.dll")>]
static member CreateStdAccessibleObject : 
        hWnd : IntPtr * 
        idObject : int * 
        refIid : Guid byref * 
        refObj : Object byref -> HResult 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.IntPtr<br />A window handle of the system-provided user interface element (a control) for which an accessible object is created.</dd><dt>idObject</dt><dd>Type: System.Int32<br />Object ID. This value is usually OBJID_CLIENT, but it may be another object identifier.</dd><dt>refIid</dt><dd>Type: System.Guid<br />Reference identifier of the requested interface. 

 This value is one of the following: IID_IAccessible, IID_IDispatch, IID_IEnumVARIANT, or IID_IUnknown.</dd><dt>refObj</dt><dd>Type: System.Object<br />A variable that receives the address of the specified interface.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />If successful, returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. 

 If not successful, returns a <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> error code.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/oleacc/nf-oleacc-createstdaccessibleobject" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/oleacc/nf-oleacc-createstdaccessibleobject</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />