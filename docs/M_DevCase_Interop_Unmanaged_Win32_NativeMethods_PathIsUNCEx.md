# NativeMethods.PathIsUNCEx Method 
 

Determines if a path string is a valid Universal Naming Convention (UNC) path, as opposed to a path based on a drive letter. 

 This function differs from <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_PathIsUNC">PathIsUNC(String)</a> in that it also allows you to extract the name of the server from the path.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("KernelBase.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static bool PathIsUNCEx(
	string path,
	ref StringBuilder refServer
)
```

**VB**<br />
``` VB
<DllImportAttribute("KernelBase.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function PathIsUNCEx ( 
	path As String,
	ByRef refServer As StringBuilder
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim path As String
Dim refServer As StringBuilder
Dim returnValue As Boolean

returnValue = NativeMethods.PathIsUNCEx(path, 
	refServer)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"KernelBase.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static bool PathIsUNCEx(
	String^ path, 
	StringBuilder^% refServer
)
```

**F#**<br />
``` F#
[<DllImportAttribute("KernelBase.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member PathIsUNCEx : 
        path : string * 
        refServer : StringBuilder byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>path</dt><dd>Type: System.String<br />A pointer to the path string.</dd><dt>refServer</dt><dd>Type: System.Text.StringBuilder<br />A pointer to a string that, when this function returns successfully, receives the server portion of the UNC path. 

 This value can be NULL if you don't need this information.</dd></dl>

#### Return Value
Type: Boolean<br />Returns `true` (`True` in Visual Basic) if the string is a valid UNC path; otherwise, `false` (`False` in Visual Basic).

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/pathcch/nf-pathcch-pathisuncex" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/pathcch/nf-pathcch-pathisuncex</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />