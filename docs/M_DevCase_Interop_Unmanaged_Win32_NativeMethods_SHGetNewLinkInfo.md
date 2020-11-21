# NativeMethods.SHGetNewLinkInfo Method 
 

Creates a name for a new shortcut based on the shortcut's proposed target. This function does not create the shortcut, just the name.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Shell32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static bool SHGetNewLinkInfo(
	string linkTo,
	string dir,
	StringBuilder name,
	out bool refMustCopy,
	SHGetNewLinkInfoFlags flags
)
```

**VB**<br />
``` VB
<DllImportAttribute("Shell32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function SHGetNewLinkInfo ( 
	linkTo As String,
	dir As String,
	name As StringBuilder,
	<OutAttribute> ByRef refMustCopy As Boolean,
	flags As SHGetNewLinkInfoFlags
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim linkTo As String
Dim dir As String
Dim name As StringBuilder
Dim refMustCopy As Boolean
Dim flags As SHGetNewLinkInfoFlags
Dim returnValue As Boolean

returnValue = NativeMethods.SHGetNewLinkInfo(linkTo, 
	dir, name, refMustCopy, flags)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Shell32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static bool SHGetNewLinkInfo(
	[InAttribute] String^ linkTo, 
	[InAttribute] String^ dir, 
	StringBuilder^ name, 
	[OutAttribute] bool% refMustCopy, 
	SHGetNewLinkInfoFlags flags
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Shell32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member SHGetNewLinkInfo : 
        linkTo : string * 
        dir : string * 
        name : StringBuilder * 
        refMustCopy : bool byref * 
        flags : SHGetNewLinkInfoFlags -> bool 

```


#### Parameters
&nbsp;<dl><dt>linkTo</dt><dd>Type: System.String<br />A pointer to the path and file name of the shortcut's target. 

 If *flags* does not contain the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_SHGetNewLinkInfoFlags">Pidl</a> value, this parameter is the address of a null-terminated string that contains the target. 

 If *flags* contains the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_SHGetNewLinkInfoFlags">Pidl</a> value, this parameter is a PIDL that represents the target.</dd><dt>dir</dt><dd>Type: System.String<br />A pointer to a null-terminated string that contains the path of the folder in which the shortcut would be created.</dd><dt>name</dt><dd>Type: System.Text.StringBuilder<br />A pointer to a string that receives the null-terminated path and file name for the shortcut. 

 This buffer is assumed to be at least MAX_PATH characters in size.</dd><dt>refMustCopy</dt><dd>Type: System.Boolean<br />A Boolean value that receives a flag indicating whether the shortcut would be copied. 

 When a shortcut to another shortcut is created, the Shell simply copies the target shortcut and modifies that copied shortcut appropriately. 

 This parameter receives a nonzero value if the target specified in *linkTo* specifies a shortcut that will cause the target shortcut to be copied. 

 This parameter receives zero if the target does not specify a shortcut that would be copied.</dd><dt>flags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_SHGetNewLinkInfoFlags">DevCase.Interop.Unmanaged.Win32.Enums.SHGetNewLinkInfoFlags</a><br />The options for the function.</dd></dl>

#### Return Value
Type: Boolean<br />Returns `true` (`True` in Visual Basic) if successful; otherwise, `false` (`False` in Visual Basic).

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/shellapi/nf-shellapi-shgetnewlinkinfoa" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/shellapi/nf-shellapi-shgetnewlinkinfoa</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />