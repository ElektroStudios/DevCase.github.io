# NativeMethods.AttachThreadInput Method 
 

Attaches or detaches the input processing mechanism of one thread to that of another thread.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static bool AttachThreadInput(
	int threadIdAttach,
	int threadIdAttachTo,
	bool attach
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function AttachThreadInput ( 
	threadIdAttach As Integer,
	threadIdAttachTo As Integer,
	attach As Boolean
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim threadIdAttach As Integer
Dim threadIdAttachTo As Integer
Dim attach As Boolean
Dim returnValue As Boolean

returnValue = NativeMethods.AttachThreadInput(threadIdAttach, 
	threadIdAttachTo, attach)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static bool AttachThreadInput(
	int threadIdAttach, 
	int threadIdAttachTo, 
	bool attach
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member AttachThreadInput : 
        threadIdAttach : int * 
        threadIdAttachTo : int * 
        attach : bool -> bool 

```


#### Parameters
&nbsp;<dl><dt>threadIdAttach</dt><dd>Type: System.Int32<br />The identifier of the thread to be attached to another thread. 

 The thread to be attached cannot be a system thread.</dd><dt>threadIdAttachTo</dt><dd>Type: System.Int32<br />The identifier of the thread to which *threadIdAttach* will be attached. This thread cannot be a system thread. 

 A thread cannot attach to itself. Therefore, *threadIdAttachTo* cannot equal idAttach</dd><dt>attach</dt><dd>Type: System.Boolean<br />If this parameter is `true` (`True` in Visual Basic), the two threads are attached. 

 If the parameter is `false` (`False` in Visual Basic), the threads are detached.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is `true` (`True` in Visual Basic). 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms681956(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms681956(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />