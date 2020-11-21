# NativeMethods.SetSuspendState Method 
 

Suspends the system by shutting power down. 

 Depending on the Hibernate parameter, the system either enters a suspend (sleep) state or hibernation (S4).

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("PowrProf.dll", ExactSpelling = true, SetLastError = true)]
public static bool SetSuspendState(
	bool hibernate,
	bool force,
	bool wakeupEventsDisabled
)
```

**VB**<br />
``` VB
<DllImportAttribute("PowrProf.dll", ExactSpelling := true, SetLastError := true>]
Public Shared Function SetSuspendState ( 
	hibernate As Boolean,
	force As Boolean,
	wakeupEventsDisabled As Boolean
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hibernate As Boolean
Dim force As Boolean
Dim wakeupEventsDisabled As Boolean
Dim returnValue As Boolean

returnValue = NativeMethods.SetSuspendState(hibernate, 
	force, wakeupEventsDisabled)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"PowrProf.dll", ExactSpelling = true, SetLastError = true)]
static bool SetSuspendState(
	bool hibernate, 
	bool force, 
	bool wakeupEventsDisabled
)
```

**F#**<br />
``` F#
[<DllImportAttribute("PowrProf.dll", ExactSpelling = true, SetLastError = true)>]
static member SetSuspendState : 
        hibernate : bool * 
        force : bool * 
        wakeupEventsDisabled : bool -> bool 

```


#### Parameters
&nbsp;<dl><dt>hibernate</dt><dd>Type: System.Boolean<br />If this parameter is `true` (`True` in Visual Basic), the system hibernates. 

 If the parameter is `false` (`False` in Visual Basic), the system is suspended.</dd><dt>force</dt><dd>Type: System.Boolean<br />This parameter has no effect.</dd><dt>wakeupEventsDisabled</dt><dd>Type: System.Boolean<br />If this parameter is `true` (`True` in Visual Basic), the system disables all wake events. 

 If the parameter is `false` (`False` in Visual Basic), any system wake events remain enabled.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the function succeeds, `false` (`False` in Visual Basic) otherwise.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/powrprof/nf-powrprof-setsuspendstate" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/powrprof/nf-powrprof-setsuspendstate</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />