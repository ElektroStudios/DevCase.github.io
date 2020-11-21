# NativeMethods.SetSystemCursor Method 
 

Enables an application to customize the system cursors. 

 It replaces the contents of the system cursor specified by the  parameter with the contents of the cursor specified by the  parameter and then destroys .

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static bool SetSystemCursor(
	IntPtr hCursor,
	SystemCursorId id
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function SetSystemCursor ( 
	hCursor As IntPtr,
	id As SystemCursorId
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hCursor As IntPtr
Dim id As SystemCursorId
Dim returnValue As Boolean

returnValue = NativeMethods.SetSystemCursor(hCursor, 
	id)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static bool SetSystemCursor(
	IntPtr hCursor, 
	SystemCursorId id
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member SetSystemCursor : 
        hCursor : IntPtr * 
        id : SystemCursorId -> bool 

```


#### Parameters
&nbsp;<dl><dt>hCursor</dt><dd>Type: System.IntPtr<br />A handle to the cursor. 

 The function replaces the contents of the system cursor specified by  parameter with the contents of the cursor handled by  parameter.</dd><dt>id</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_SystemCursorId">DevCase.Interop.Unmanaged.Win32.Enums.SystemCursorId</a><br />The system cursor to replace with the contents of  parameter.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic).

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms648395%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms648395%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />