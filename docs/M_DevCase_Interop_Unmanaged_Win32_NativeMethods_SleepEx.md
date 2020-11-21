# NativeMethods.SleepEx Method 
 

Suspends the current thread until the specified condition is met. Execution resumes when one of the following occurs: 

 - An I/O completion callback function is called. 

 - An asynchronous procedure call (APC) is queued to the thread. 

 - The time-out interval elapses.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", SetLastError = true)]
public static uint SleepEx(
	int milliseconds,
	bool alertable
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", SetLastError := true>]
Public Shared Function SleepEx ( 
	milliseconds As Integer,
	alertable As Boolean
) As UInteger
```

**VB Usage**<br />
``` VB Usage
Dim milliseconds As Integer
Dim alertable As Boolean
Dim returnValue As UInteger

returnValue = NativeMethods.SleepEx(milliseconds, 
	alertable)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", SetLastError = true)]
static unsigned int SleepEx(
	int milliseconds, 
	bool alertable
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", SetLastError = true)>]
static member SleepEx : 
        milliseconds : int * 
        alertable : bool -> uint32 

```


#### Parameters
&nbsp;<dl><dt>milliseconds</dt><dd>Type: System.Int32<br />The time interval for which execution is to be suspended, in milliseconds. 

 A value of zero causes the thread to relinquish the remainder of its time slice to any other thread that is ready to run. 

 If there are no other threads ready to run, the function returns immediately, and the thread continues execution. 

 A value of INFINITE (-1) indicates that the suspension should not time out.</dd><dt>alertable</dt><dd>Type: System.Boolean<br />If this parameter is `false` (`False` in Visual Basic), the function does not return until the time-out period has elapsed. If an I/O completion callback occurs, the function does not return and the I/O completion function is not executed. If an APC is queued to the thread, the function does not return and the APC function is not executed. 

 If the parameter is `true` (`True` in Visual Basic) and the thread that called this function is the same thread that called the extended I/O function (ReadFileEx or WriteFileEx), the function returns when either the time-out period has elapsed or when an I/O completion callback function occurs. If an I/O completion callback occurs, the I/O completion function is called. If an APC is queued to the thread (QueueUserAPC), the function returns when either the timer-out period has elapsed or when the APC function is called.</dd></dl>

#### Return Value
Type: UInt32<br />\[Missing <returns> documentation for "M:DevCase.Interop.Unmanaged.Win32.NativeMethods.SleepEx(System.Int32,System.Boolean)"\]

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/synchapi/nf-synchapi-sleepex" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/synchapi/nf-synchapi-sleepex</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />