# NativeMethods.IsGuiThread Method 
 

Determines whether the calling thread is already a GUI thread. 

 It can also optionally convert the thread to a GUI thread.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", EntryPoint = "IsGUIThread", SetLastError = true)]
public static bool IsGuiThread(
	bool convertToGuiThread
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", EntryPoint := "IsGUIThread", SetLastError := true>]
Public Shared Function IsGuiThread ( 
	convertToGuiThread As Boolean
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim convertToGuiThread As Boolean
Dim returnValue As Boolean

returnValue = NativeMethods.IsGuiThread(convertToGuiThread)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", EntryPoint = L"IsGUIThread", SetLastError = true)]
static bool IsGuiThread(
	bool convertToGuiThread
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", EntryPoint = "IsGUIThread", SetLastError = true)>]
static member IsGuiThread : 
        convertToGuiThread : bool -> bool 

```


#### Parameters
&nbsp;<dl><dt>convertToGuiThread</dt><dd>Type: System.Boolean<br />If this value is `true` (`True` in Visual Basic), and if the thread is not a GUI thread, converts the thread to a GUI thread.</dd></dl>

#### Return Value
Type: Boolean<br />The function returns `true` (`True` in Visual Basic) value in the following situations: 

 • If the calling thread is already a GUI thread. 

 • If convertToGuiThread is `true` (`True` in Visual Basic) and the function successfully converts the thread to a GUI thread. 



 Otherwise, the function returns `false` (`False` in Visual Basic).

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms633525%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms633525%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />