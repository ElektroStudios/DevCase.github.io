# NativeMethods.CreateBindCtx Method 
 

Returns a pointer to an implementation of IBindCtx (a bind context object). 

 This object stores information about a particular moniker-binding operation.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Ole32.dll")]
public static HResult CreateBindCtx(
	[OptionalAttribute] uint reserved,
	out IBindCtx refBindContext
)
```

**VB**<br />
``` VB
<DllImportAttribute("Ole32.dll">]
Public Shared Function CreateBindCtx ( 
	<OptionalAttribute> reserved As UInteger,
	<OutAttribute> ByRef refBindContext As IBindCtx
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim reserved As UInteger
Dim refBindContext As IBindCtx
Dim returnValue As HResult

returnValue = NativeMethods.CreateBindCtx(reserved, 
	refBindContext)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Ole32.dll")]
static HResult CreateBindCtx(
	[OptionalAttribute] unsigned int reserved, 
	[OutAttribute] IBindCtx^% refBindContext
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Ole32.dll")>]
static member CreateBindCtx : 
        [<OptionalAttribute>] reserved : uint32 * 
        refBindContext : IBindCtx byref -> HResult 

```


#### Parameters
&nbsp;<dl><dt>reserved (Optional)</dt><dd>Type: System.UInt32<br />This parameter is reserved and must be 0.</dd><dt>refBindContext</dt><dd>Type: System.Runtime.InteropServices.ComTypes.IBindCtx<br />Address of an IBindCtx pointer variable that receives the interface pointer to the new bind context object. 

 When the function is successful, the caller is responsible for calling Release on the bind context. 

 A value of a null reference (`Nothing` in Visual Basic) for the *refBindContext* value indicates that an error occurred.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />Returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a> on success, or other <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> if an error occurs.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms678542%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms678542%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />