# NativeMethods.DestroyIcon Method 
 

Destroys an icon and frees any memory the icon occupied.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static bool DestroyIcon(
	IntPtr hIcon
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function DestroyIcon ( 
	hIcon As IntPtr
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hIcon As IntPtr
Dim returnValue As Boolean

returnValue = NativeMethods.DestroyIcon(hIcon)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static bool DestroyIcon(
	IntPtr hIcon
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member DestroyIcon : 
        hIcon : IntPtr -> bool 

```


#### Parameters
&nbsp;<dl><dt>hIcon</dt><dd>Type: System.IntPtr<br />A handle to the icon to be destroyed. 

 The icon must not be in use.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms648063%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms648063%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />