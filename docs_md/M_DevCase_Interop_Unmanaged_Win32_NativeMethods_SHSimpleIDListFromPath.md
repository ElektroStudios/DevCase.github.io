# NativeMethods.SHSimpleIDListFromPath Method 
 

**Note: This API is now obsolete.**

Returns a pointer to an ITEMIDLIST structure when passed a path.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Shell32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ExactSpelling = true, ThrowOnUnmappableChar = true, SetLastError = true)]
[ObsoleteAttribute("Deprecated.", false)]
public static PIDL SHSimpleIDListFromPath(
	string path
)
```

**VB**<br />
``` VB
<DllImportAttribute("Shell32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ExactSpelling := true, ThrowOnUnmappableChar := true, SetLastError := true>]
<ObsoleteAttribute("Deprecated.", false)>
Public Shared Function SHSimpleIDListFromPath ( 
	path As String
) As PIDL
```

**VB Usage**<br />
``` VB Usage
Dim path As String
Dim returnValue As PIDL

returnValue = NativeMethods.SHSimpleIDListFromPath(path)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Shell32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ExactSpelling = true, ThrowOnUnmappableChar = true, SetLastError = true)]
[ObsoleteAttribute(L"Deprecated.", false)]
static PIDL^ SHSimpleIDListFromPath(
	String^ path
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Shell32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ExactSpelling = true, ThrowOnUnmappableChar = true, SetLastError = true)>]
[<ObsoleteAttribute("Deprecated.", false)>]
static member SHSimpleIDListFromPath : 
        path : string -> PIDL 

```


#### Parameters
&nbsp;<dl><dt>path</dt><dd>Type: System.String<br />A pointer to a null-terminated string that contains the path to be converted to a PIDL.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_PIDL">PIDL</a><br />Returns a pointer to an ITEMIDLIST structure if successful, or NULL otherwise.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/shobjidl_core/nf-shobjidl_core-shsimpleidlistfrompath" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/shobjidl_core/nf-shobjidl_core-shsimpleidlistfrompath</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />