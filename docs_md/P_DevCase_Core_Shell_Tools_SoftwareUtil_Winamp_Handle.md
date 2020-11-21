# SoftwareUtil.Winamp.Handle Property 
 

Gets a window handle to the Winamp process main window.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static IntPtr Handle { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property Handle As IntPtr
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As IntPtr

value = SoftwareUtil.Winamp.Handle

```

**C++**<br />
``` C++
public:
static property IntPtr Handle {
	IntPtr get ();
}
```

**F#**<br />
``` F#
static member Handle : IntPtr with get

```


#### Property Value
Type: IntPtr<br />If Winamp process is running, the return value is a handle to the Winamp process main window. 

 If Winamp process is not running, the return value is Zero.

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_SoftwareUtil_Winamp">SoftwareUtil.Winamp Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />