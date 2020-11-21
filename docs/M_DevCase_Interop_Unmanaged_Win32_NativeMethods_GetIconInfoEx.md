# NativeMethods.GetIconInfoEx Method 
 

Retrieves information about the specified icon or cursor.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static bool GetIconInfoEx(
	IntPtr hIcon,
	ref IconInfoEx refIconInfoEx
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function GetIconInfoEx ( 
	hIcon As IntPtr,
	ByRef refIconInfoEx As IconInfoEx
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hIcon As IntPtr
Dim refIconInfoEx As IconInfoEx
Dim returnValue As Boolean

returnValue = NativeMethods.GetIconInfoEx(hIcon, 
	refIconInfoEx)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static bool GetIconInfoEx(
	IntPtr hIcon, 
	IconInfoEx% refIconInfoEx
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member GetIconInfoEx : 
        hIcon : IntPtr * 
        refIconInfoEx : IconInfoEx byref -> bool 

```


#### Parameters
&nbsp;<dl><dt>hIcon</dt><dd>Type: System.IntPtr<br />A handle to the icon or cursor.</dd><dt>refIconInfoEx</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_IconInfoEx">DevCase.Interop.Unmanaged.Win32.Structures.IconInfoEx</a><br />A pointer to an <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_IconInfoEx">IconInfoEx</a> structure that receives the information.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic), and the function fills in the members of the specified <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_IconInfoEx">IconInfoEx</a> structure. 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms648071(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms648071(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />