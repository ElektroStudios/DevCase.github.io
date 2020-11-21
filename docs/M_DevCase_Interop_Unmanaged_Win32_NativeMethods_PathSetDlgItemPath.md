# NativeMethods.PathSetDlgItemPath Method 
 

Sets the text of a child control in a window or dialog box, using PathCompactPath function to ensure the path fits in the control.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("ShlwApi.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static void PathSetDlgItemPath(
	IntPtr hDlg,
	int id,
	string path
)
```

**VB**<br />
``` VB
<DllImportAttribute("ShlwApi.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Sub PathSetDlgItemPath ( 
	hDlg As IntPtr,
	id As Integer,
	path As String
)
```

**VB Usage**<br />
``` VB Usage
Dim hDlg As IntPtr
Dim id As Integer
Dim path As StringNativeMethods.PathSetDlgItemPath(hDlg, id, 
	path)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"ShlwApi.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static void PathSetDlgItemPath(
	IntPtr hDlg, 
	int id, 
	String^ path
)
```

**F#**<br />
``` F#
[<DllImportAttribute("ShlwApi.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member PathSetDlgItemPath : 
        hDlg : IntPtr * 
        id : int * 
        path : string -> unit 

```


#### Parameters
&nbsp;<dl><dt>hDlg</dt><dd>Type: System.IntPtr<br />A handle to the dialog box or window.</dd><dt>id</dt><dd>Type: System.Int32<br />The identifier of the control.</dd><dt>path</dt><dd>Type: System.String<br />A string of maximum length MAX_PATH that contains the path to set in the control.</dd></dl>

## Remarks
<a href="https://technet.microsoft.com/es-es/evalcenter/bb773752%28v=vs.110%29.aspx" target="_blank">https://technet.microsoft.com/es-es/evalcenter/bb773752%28v=vs.110%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />