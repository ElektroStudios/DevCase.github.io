# Delegates.ApplicationRecoveryCallback Delegate
 

Application-defined callback function used to save data and application state information in the event the application encounters an unhandled exception or becomes unresponsive.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public delegate uint ApplicationRecoveryCallback(
	IntPtr callbackParam
)
```

**VB**<br />
``` VB
Public Delegate Function ApplicationRecoveryCallback ( 
	callbackParam As IntPtr
) As UInteger
```

**VB Usage**<br />
``` VB Usage
Dim instance As New ApplicationRecoveryCallback(AddressOf HandlerMethod)
```

**C++**<br />
``` C++
public delegate unsigned int ApplicationRecoveryCallback(
	IntPtr callbackParam
)
```

**F#**<br />
``` F#
type ApplicationRecoveryCallback = 
    delegate of 
        callbackParam : IntPtr -> uint32
```


#### Parameters
&nbsp;<dl><dt>callbackParam</dt><dd>Type: System.IntPtr<br />Context information specified when you called the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_RegisterApplicationRecoveryCallback">RegisterApplicationRecoveryCallback(Delegates.ApplicationRecoveryCallback, IntPtr, UInt32, UInt32)</a> function to register for recovery.</dd></dl>

#### Return Value
Type: UInt32<br />The return value is not used and should be 0.

## Remarks
<a href="https://docs.microsoft.com/en-us/previous-versions/windows/desktop/legacy/aa373202(v=vs.85)" target="_blank">https://docs.microsoft.com/en-us/previous-versions/windows/desktop/legacy/aa373202(v=vs.85)</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />