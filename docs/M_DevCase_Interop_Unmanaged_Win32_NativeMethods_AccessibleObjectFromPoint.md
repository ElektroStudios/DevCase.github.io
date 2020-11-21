# NativeMethods.AccessibleObjectFromPoint Method (NativePoint, IAccessible, Object)
 

Retrieves the address of the IAccessible interface pointer for the object displayed at a specified point on the screen.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("OleAcc.dll")]
public static HResult AccessibleObjectFromPoint(
	NativePoint ptScreen,
	out IAccessible refAccessible,
	out Object refChild
)
```

**VB**<br />
``` VB
<DllImportAttribute("OleAcc.dll">]
Public Shared Function AccessibleObjectFromPoint ( 
	ptScreen As NativePoint,
	<OutAttribute> ByRef refAccessible As IAccessible,
	<OutAttribute> ByRef refChild As Object
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim ptScreen As NativePoint
Dim refAccessible As IAccessible
Dim refChild As Object
Dim returnValue As HResult

returnValue = NativeMethods.AccessibleObjectFromPoint(ptScreen, 
	refAccessible, refChild)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"OleAcc.dll")]
static HResult AccessibleObjectFromPoint(
	NativePoint ptScreen, 
	[OutAttribute] IAccessible^% refAccessible, 
	[OutAttribute] Object^% refChild
)
```

**F#**<br />
``` F#
[<DllImportAttribute("OleAcc.dll")>]
static member AccessibleObjectFromPoint : 
        ptScreen : NativePoint * 
        refAccessible : IAccessible byref * 
        refChild : Object byref -> HResult 

```


#### Parameters
&nbsp;<dl><dt>ptScreen</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativePoint">DevCase.Interop.Unmanaged.Win32.Structures.NativePoint</a><br />Specifies, in physical screen coordinates, the point that is examined.</dd><dt>refAccessible</dt><dd>Type: Accessibility.IAccessible<br />A variable that receives the address of the object's IAccessible interface.</dd><dt>refChild</dt><dd>Type: System.Object<br />A `VARIANT` structure that specifies whether the IAccessible interface pointer that is returned in *refAccessible* belongs to the object displayed at the specified point, or to the parent of the element at the specified point. 

 The `vt` member of the `VARIANT` structure is always VT_I4. 

 If the `lVal` member is CHILDID_SELF, then the IAccessible interface pointer at *refAccessible* belongs to the object at the point. 

 If the `lVal` member is not CHILDID_SELF, *refAccessible* is the address of the IAccessible interface of the child element's parent object. 

 Clients must call VariantClear on the retrieved `VARIANT` structure when finished using it.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />If successful, returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. 

 If not successful, returns a <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> error code.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/oleacc/nf-oleacc-accessibleobjectfrompoint" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/oleacc/nf-oleacc-accessibleobjectfrompoint</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_AccessibleObjectFromPoint">AccessibleObjectFromPoint Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />