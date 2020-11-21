# NativeMethods.SHAddToRecentDocs Method (ShellAddToRecentDocsFlags, String)
 

Notifies the system that an item has been accessed, for the purposes of tracking those items used most recently and most frequently. 

 This function can also be used to clear all usage data.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Shell32.dll", ExactSpelling = true, SetLastError = true)]
[SecurityCriticalAttribute]
public static void SHAddToRecentDocs(
	ShellAddToRecentDocsFlags flags,
	string path
)
```

**VB**<br />
``` VB
<DllImportAttribute("Shell32.dll", ExactSpelling := true, SetLastError := true>]
<SecurityCriticalAttribute>
Public Shared Sub SHAddToRecentDocs ( 
	flags As ShellAddToRecentDocsFlags,
	path As String
)
```

**VB Usage**<br />
``` VB Usage
Dim flags As ShellAddToRecentDocsFlags
Dim path As StringNativeMethods.SHAddToRecentDocs(flags, path)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Shell32.dll", ExactSpelling = true, SetLastError = true)]
[SecurityCriticalAttribute]
static void SHAddToRecentDocs(
	ShellAddToRecentDocsFlags flags, 
	String^ path
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Shell32.dll", ExactSpelling = true, SetLastError = true)>]
[<SecurityCriticalAttribute>]
static member SHAddToRecentDocs : 
        flags : ShellAddToRecentDocsFlags * 
        path : string -> unit 

```


#### Parameters
&nbsp;<dl><dt>flags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_ShellAddToRecentDocsFlags">DevCase.Interop.Unmanaged.Win32.Enums.ShellAddToRecentDocsFlags</a><br />flags that ndicates the form of the information pointed to by the pv parameter.</dd><dt>path</dt><dd>Type: System.String<br />A pointer to data that identifies the item that has been accessed. 

 Set this parameter to NULL to clear all usage data on all items.</dd></dl>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/bb762105%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/bb762105%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_SHAddToRecentDocs">SHAddToRecentDocs Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />