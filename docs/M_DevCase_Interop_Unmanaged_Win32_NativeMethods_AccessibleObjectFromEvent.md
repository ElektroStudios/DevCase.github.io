# NativeMethods.AccessibleObjectFromEvent Method 
 

Retrieves the address of the IAccessible interface for the object that generated the event that is currently being processed by the client's event hook function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("OleAcc.dll")]
public static HResult AccessibleObjectFromEvent(
	IntPtr hWnd,
	uint id,
	uint childId,
	out IAccessible refAccessible,
	out Object refChild
)
```

**VB**<br />
``` VB
<DllImportAttribute("OleAcc.dll">]
Public Shared Function AccessibleObjectFromEvent ( 
	hWnd As IntPtr,
	id As UInteger,
	childId As UInteger,
	<OutAttribute> ByRef refAccessible As IAccessible,
	<OutAttribute> ByRef refChild As Object
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As IntPtr
Dim id As UInteger
Dim childId As UInteger
Dim refAccessible As IAccessible
Dim refChild As Object
Dim returnValue As HResult

returnValue = NativeMethods.AccessibleObjectFromEvent(hWnd, 
	id, childId, refAccessible, refChild)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"OleAcc.dll")]
static HResult AccessibleObjectFromEvent(
	IntPtr hWnd, 
	unsigned int id, 
	unsigned int childId, 
	[OutAttribute] IAccessible^% refAccessible, 
	[OutAttribute] Object^% refChild
)
```

**F#**<br />
``` F#
[<DllImportAttribute("OleAcc.dll")>]
static member AccessibleObjectFromEvent : 
        hWnd : IntPtr * 
        id : uint32 * 
        childId : uint32 * 
        refAccessible : IAccessible byref * 
        refChild : Object byref -> HResult 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.IntPtr<br />Specifies the window handle of the window that generated the event. 

 This value must be the window handle that is sent to the event hook function.</dd><dt>id</dt><dd>Type: System.UInt32<br />Specifies the object ID of the object that generated the event. 

 This value must be the object ID that is sent to the event hook function.</dd><dt>childId</dt><dd>Type: System.UInt32<br />Specifies whether the event was triggered by an object or one of its child elements. 

 If the object triggered the event, *childID* is CHILDID_SELF. 

 If a child element triggered the event, *childID* is the element's child ID. This value must be the child ID that is sent to the event hook function.</dd><dt>refAccessible</dt><dd>Type: Accessibility.IAccessible<br />
Address of a pointer variable that receives the address of an IAccessible interface. 

 The interface is either for the object that generated the event, or for the parent of the element that generated the event.</dd><dt>refChild</dt><dd>Type: System.Object<br />A `VARIANT` structure that specifies the child ID that can be used to access information about the UI element.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />If successful, returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. 

 If not successful, returns a <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> error code.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/oleacc/nf-oleacc-accessibleobjectfromevent" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/oleacc/nf-oleacc-accessibleobjectfromevent</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />