# NativeMethods.SHParseDisplayName Method (String, IBindCtx, PIDL, ShellItemAttributesMask, ShellItemAttributesMask)
 

Translates a Shell namespace object's display name into an item identifier list (PIDL) and returns the attributes of the object. 

 This function is the preferred method to convert a string to a pointer to an item identifier list (PIDL).

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Shell32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ExactSpelling = true, ThrowOnUnmappableChar = true)]
public static HResult SHParseDisplayName(
	string name,
	[OptionalAttribute] IBindCtx bindContext,
	out PIDL refPidl,
	ShellItemAttributesMask flagsIn,
	out ShellItemAttributesMask flagsOut
)
```

**VB**<br />
``` VB
<DllImportAttribute("Shell32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ExactSpelling := true, ThrowOnUnmappableChar := true>]
Public Shared Function SHParseDisplayName ( 
	name As String,
	<OptionalAttribute> bindContext As IBindCtx,
	<OutAttribute> ByRef refPidl As PIDL,
	flagsIn As ShellItemAttributesMask,
	<OutAttribute> ByRef flagsOut As ShellItemAttributesMask
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim name As String
Dim bindContext As IBindCtx
Dim refPidl As PIDL
Dim flagsIn As ShellItemAttributesMask
Dim flagsOut As ShellItemAttributesMask
Dim returnValue As HResult

returnValue = NativeMethods.SHParseDisplayName(name, 
	bindContext, refPidl, flagsIn, flagsOut)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Shell32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ExactSpelling = true, ThrowOnUnmappableChar = true)]
static HResult SHParseDisplayName(
	String^ name, 
	[OptionalAttribute] [InAttribute] IBindCtx^ bindContext, 
	[OutAttribute] PIDL^% refPidl, 
	ShellItemAttributesMask flagsIn, 
	[OutAttribute] ShellItemAttributesMask% flagsOut
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Shell32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ExactSpelling = true, ThrowOnUnmappableChar = true)>]
static member SHParseDisplayName : 
        name : string * 
        [<OptionalAttribute>] bindContext : IBindCtx * 
        refPidl : PIDL byref * 
        flagsIn : ShellItemAttributesMask * 
        flagsOut : ShellItemAttributesMask byref -> HResult 

```


#### Parameters
&nbsp;<dl><dt>name</dt><dd>Type: System.String<br />A pointer to a zero-terminated wide string that contains the display name to parse.</dd><dt>bindContext (Optional)</dt><dd>Type: System.Runtime.InteropServices.ComTypes.IBindCtx<br />A bind context that controls the parsing operation. 

 This parameter is normally set to NULL.</dd><dt>refPidl</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_PIDL">DevCase.Interop.Unmanaged.PIDL</a><br />The address of a pointer to a variable of type ITEMIDLIST that receives the item identifier list for the object. 

 If an error occurs, then this parameter is set to NULL.</dd><dt>flagsIn</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ShellItemAttributesMask">DevCase.Interop.Unmanaged.Win32.Enums.ShellItemAttributesMask</a><br />A value that specifies the attributes to query. To query for one or more attributes, initialize this parameter with the flags that represent the attributes of interest.</dd><dt>flagsOut</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ShellItemAttributesMask">DevCase.Interop.Unmanaged.Win32.Enums.ShellItemAttributesMask</a><br />On return, *flagsOut* receive those attributes that are `true` (`True` in Visual Basic) for the object and were requested in *flagsIn* are set.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />If this function succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. Otherwise, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> error code.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/shlobj_core/nf-shlobj_core-shparsedisplayname" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/shlobj_core/nf-shlobj_core-shparsedisplayname</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_SHParseDisplayName">SHParseDisplayName Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />