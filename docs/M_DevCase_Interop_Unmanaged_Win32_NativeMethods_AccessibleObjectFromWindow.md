# NativeMethods.AccessibleObjectFromWindow Method 
 

Retrieves the address of the specified interface for the object associated with the specified window.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("OleAcc.dll", SetLastError = true)]
public static HResult AccessibleObjectFromWindow(
	IntPtr hWnd,
	uint id,
	ref Guid refRiid,
	out Object refObject
)
```

**VB**<br />
``` VB
<DllImportAttribute("OleAcc.dll", SetLastError := true>]
Public Shared Function AccessibleObjectFromWindow ( 
	hWnd As IntPtr,
	id As UInteger,
	ByRef refRiid As Guid,
	<OutAttribute> ByRef refObject As Object
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As IntPtr
Dim id As UInteger
Dim refRiid As Guid
Dim refObject As Object
Dim returnValue As HResult

returnValue = NativeMethods.AccessibleObjectFromWindow(hWnd, 
	id, refRiid, refObject)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"OleAcc.dll", SetLastError = true)]
static HResult AccessibleObjectFromWindow(
	IntPtr hWnd, 
	unsigned int id, 
	Guid% refRiid, 
	[InAttribute] [OutAttribute] Object^% refObject
)
```

**F#**<br />
``` F#
[<DllImportAttribute("OleAcc.dll", SetLastError = true)>]
static member AccessibleObjectFromWindow : 
        hWnd : IntPtr * 
        id : uint32 * 
        refRiid : Guid byref * 
        refObject : Object byref -> HResult 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.IntPtr<br />Specifies the handle of a window for which an object is to be retrieved. 

 To retrieve an interface pointer to the cursor or caret object, specify Zero and use the appropriate object ID in *id* parameter.</dd><dt>id</dt><dd>Type: System.UInt32<br />Specifies the object ID. 

 This value is one of the standard object identifier constants or a custom object ID such as OBJID_NATIVEOM, which is the object ID for the Office native object model.</dd><dt>refRiid</dt><dd>Type: System.Guid<br />Specifies the reference identifier of the requested interface. 

 This value is either IID_IAccessible or IID_IDispatch, but it can also be IID_IUnknown, or the IID of any interface that the object is expected to support.</dd><dt>refObject</dt><dd>Type: System.Object<br />Address of a pointer variable that receives the address of the specified interface.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />If the function succeeds, the return value is <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. 

 If the function fails, the return value is a different <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> value.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/oleacc/nf-oleacc-accessibleobjectfromwindow" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/oleacc/nf-oleacc-accessibleobjectfromwindow</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />