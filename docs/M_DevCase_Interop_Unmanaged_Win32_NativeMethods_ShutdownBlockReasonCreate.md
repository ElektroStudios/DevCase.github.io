# NativeMethods.ShutdownBlockReasonCreate Method 
 

Indicates that the system cannot be shut down and sets a reason string to be displayed to the user if system shutdown is initiated.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", ExactSpelling = true, SetLastError = true)]
public static bool ShutdownBlockReasonCreate(
	IntPtr hWnd,
	string reason
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function ShutdownBlockReasonCreate ( 
	hWnd As IntPtr,
	reason As String
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As IntPtr
Dim reason As String
Dim returnValue As Boolean

returnValue = NativeMethods.ShutdownBlockReasonCreate(hWnd, 
	reason)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", ExactSpelling = true, SetLastError = true)]
static bool ShutdownBlockReasonCreate(
	IntPtr hWnd, 
	String^ reason
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", ExactSpelling = true, SetLastError = true)>]
static member ShutdownBlockReasonCreate : 
        hWnd : IntPtr * 
        reason : string -> bool 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.IntPtr<br />A handle to the main window of the application.</dd><dt>reason</dt><dd>Type: System.String<br />The reason the application must block system shutdown. 

 This string will be truncated for display purposes after MAX_STR_BLOCKREASON characters.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-shutdownblockreasoncreate" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winuser/nf-winuser-shutdownblockreasoncreate</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />