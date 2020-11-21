# NativeMethods.DestroyCursor Method 
 

Destroys a cursor and frees any memory the cursor occupied. 

 Do not use this function to destroy a shared cursor.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static bool DestroyCursor(
	IntPtr hCursor
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function DestroyCursor ( 
	hCursor As IntPtr
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hCursor As IntPtr
Dim returnValue As Boolean

returnValue = NativeMethods.DestroyCursor(hCursor)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static bool DestroyCursor(
	IntPtr hCursor
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member DestroyCursor : 
        hCursor : IntPtr -> bool 

```


#### Parameters
&nbsp;<dl><dt>hCursor</dt><dd>Type: System.IntPtr<br />A handle to the cursor to be destroyed. 

 The cursor must not be in use.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms648386%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms648386%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />