# NativeMethods.AccessibleChildren Method 
 

Retrieves the child ID or IDispatch of each child within an accessible container object.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("OleAcc.dll", SetLastError = true)]
public static HResult AccessibleChildren(
	IAccessible container,
	int childStart,
	int childrenCount,
	Object[] children,
	ref int refObtained
)
```

**VB**<br />
``` VB
<DllImportAttribute("OleAcc.dll", SetLastError := true>]
Public Shared Function AccessibleChildren ( 
	container As IAccessible,
	childStart As Integer,
	childrenCount As Integer,
	<OutAttribute> children As Object(),
	ByRef refObtained As Integer
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim container As IAccessible
Dim childStart As Integer
Dim childrenCount As Integer
Dim children As Object()
Dim refObtained As Integer
Dim returnValue As HResult

returnValue = NativeMethods.AccessibleChildren(container, 
	childStart, childrenCount, children, 
	refObtained)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"OleAcc.dll", SetLastError = true)]
static HResult AccessibleChildren(
	IAccessible^ container, 
	int childStart, 
	int childrenCount, 
	[OutAttribute] array<Object^>^ children, 
	int% refObtained
)
```

**F#**<br />
``` F#
[<DllImportAttribute("OleAcc.dll", SetLastError = true)>]
static member AccessibleChildren : 
        container : IAccessible * 
        childStart : int * 
        childrenCount : int * 
        children : Object[] byref * 
        refObtained : int byref -> HResult 

```


#### Parameters
&nbsp;<dl><dt>container</dt><dd>Type: Accessibility.IAccessible<br />Pointer to the container object's IAccessible interface.</dd><dt>childStart</dt><dd>Type: System.Int32<br />Specifies the zero-based index of the first child that is retrieved. 

 This parameter is an index, not a child ID, and it is usually is set to zero (0).</dd><dt>childrenCount</dt><dd>Type: System.Int32<br />Specifies the number of children to retrieve. 

 To retrieve the current number of children, an application calls IAccessible::get_accChildCount.</dd><dt>children</dt><dd>Type: System.Object[]<br />Pointer to an array of VARIANT structures that receives information about the container's children. 

 If the vt member of an array element is VT_I4, then the lVal member for that element is the child ID. 

 If the vt member of an array element is VT_DISPATCH, then the pdispVal member for that element is the address of the child object's IDispatch interface.</dd><dt>refObtained</dt><dd>Type: System.Int32<br />Address of a variable that receives the number of elements in the *children* array that is populated by the AccessibleChildren(IAccessible, Int32, Int32, Object[], Int32) function. 

 This value is the same as that of the *childrenCount* parameter; however, if you request more children than exist, this value will be less than that of *childrenCount*.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />If the function succeeds, the return value is <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. 

 If the function fails, the return value is a different <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> value.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/oleacc/nf-oleacc-accessiblechildren" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/oleacc/nf-oleacc-accessiblechildren</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />