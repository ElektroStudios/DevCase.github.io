# NativeUtil.FailFastIfZero Method (IntPtr)
 

Evaluates the supplied unmanaged return value and, if it is equal to Zero, immediately terminates the calling process after writing the corresponding Win32 error message to the Windows Application event log. 

 This exception uses the last Win32 error code (GetLastWin32Error()) as error message.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Tools">DevCase.Interop.Unmanaged.Tools</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static void FailFastIfZero(
	IntPtr returnValue
)
```

**VB**<br />
``` VB
Public Shared Sub FailFastIfZero ( 
	returnValue As IntPtr
)
```

**VB Usage**<br />
``` VB Usage
Dim returnValue As IntPtrNativeUtil.FailFastIfZero(returnValue)
```

**C++**<br />
``` C++
public:
static void FailFastIfZero(
	IntPtr returnValue
)
```

**F#**<br />
``` F#
static member FailFastIfZero : 
        returnValue : IntPtr -> unit 

```


#### Parameters
&nbsp;<dl><dt>returnValue</dt><dd>Type: System.IntPtr<br />The return value to test.</dd></dl>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Tools_NativeUtil">NativeUtil Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Tools_NativeUtil_FailFastIfZero">FailFastIfZero Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Tools">DevCase.Interop.Unmanaged.Tools Namespace</a><br />