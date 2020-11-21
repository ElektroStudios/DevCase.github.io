# NativeMethods.GetIconInfo Method 
 

Retrieves information about the specified icon or cursor.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static bool GetIconInfo(
	IntPtr hIcon,
	ref IconInfo refIconInfo
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function GetIconInfo ( 
	hIcon As IntPtr,
	ByRef refIconInfo As IconInfo
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hIcon As IntPtr
Dim refIconInfo As IconInfo
Dim returnValue As Boolean

returnValue = NativeMethods.GetIconInfo(hIcon, 
	refIconInfo)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static bool GetIconInfo(
	IntPtr hIcon, 
	IconInfo% refIconInfo
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member GetIconInfo : 
        hIcon : IntPtr * 
        refIconInfo : IconInfo byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>hIcon</dt><dd>Type: System.IntPtr<br />A handle to the icon or cursor.</dd><dt>refIconInfo</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_IconInfo">DevCase.Interop.Unmanaged.Win32.Structures.IconInfo</a><br />A pointer to an <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_IconInfo">IconInfo</a> structure that receives the information.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic), and the function fills in the members of the specified <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_IconInfo">IconInfo</a> structure. 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms648070%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms648070%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />