# NativeMethods.LaunchInternetControlPanel Method 
 

Launches the Internet Properties dialog box with the General tab displayed.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("InetCpl.cpl", SetLastError = true)]
public static int LaunchInternetControlPanel(
	IntPtr hWnd
)
```

**VB**<br />
``` VB
<DllImportAttribute("InetCpl.cpl", SetLastError := true>]
Public Shared Function LaunchInternetControlPanel ( 
	hWnd As IntPtr
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As IntPtr
Dim returnValue As Integer

returnValue = NativeMethods.LaunchInternetControlPanel(hWnd)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"InetCpl.cpl", SetLastError = true)]
static int LaunchInternetControlPanel(
	IntPtr hWnd
)
```

**F#**<br />
``` F#
[<DllImportAttribute("InetCpl.cpl", SetLastError = true)>]
static member LaunchInternetControlPanel : 
        hWnd : IntPtr -> int 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.IntPtr<br />A handle To the parent window Of the Internet Properties dialog box. This parameter can be Zero.</dd></dl>

#### Return Value
Type: Int32<br />Returns `true` (`True` in Visual Basic) if successful, or `false` (`False` in Visual Basic) otherwise.

## Remarks
<a href="https://msdn.microsoft.com/en-us/ie/aa753678(v=vs.100)" target="_blank">https://msdn.microsoft.com/en-us/ie/aa753678(v=vs.100)</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />