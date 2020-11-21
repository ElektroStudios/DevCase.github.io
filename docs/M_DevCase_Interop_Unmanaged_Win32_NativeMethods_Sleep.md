# NativeMethods.Sleep Method 
 

Suspends the execution of the current thread until the time-out interval elapses. 

 To enter an alertable wait state, use the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_SleepEx">SleepEx(Int32, Boolean)</a> function.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", SetLastError = true)]
public static void Sleep(
	int milliseconds
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", SetLastError := true>]
Public Shared Sub Sleep ( 
	milliseconds As Integer
)
```

**VB Usage**<br />
``` VB Usage
Dim milliseconds As Integer

NativeMethods.Sleep(milliseconds)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", SetLastError = true)]
static void Sleep(
	int milliseconds
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", SetLastError = true)>]
static member Sleep : 
        milliseconds : int -> unit 

```


#### Parameters
&nbsp;<dl><dt>milliseconds</dt><dd>Type: System.Int32<br />The time interval for which execution is to be suspended, in milliseconds. 

 A value of zero causes the thread to relinquish the remainder of its time slice to any other thread that is ready to run. 

 If there are no other threads ready to run, the function returns immediately, and the thread continues execution. 

 A value of INFINITE (-1) indicates that the suspension should not time out.</dd></dl>

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/synchapi/nf-synchapi-sleep" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/synchapi/nf-synchapi-sleep</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />