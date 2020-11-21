# NativeMethods.AbortSystemShutdown Method 
 

Aborts a system shutdown that has been initiated.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("AdvApi32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static bool AbortSystemShutdown(
	string machineName = "127.0.0.1"
)
```

**VB**<br />
``` VB
<DllImportAttribute("AdvApi32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function AbortSystemShutdown ( 
	Optional machineName As String = "127.0.0.1"
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim machineName As String
Dim returnValue As Boolean

returnValue = NativeMethods.AbortSystemShutdown(machineName)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"AdvApi32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static bool AbortSystemShutdown(
	String^ machineName = L"127.0.0.1"
)
```

**F#**<br />
``` F#
[<DllImportAttribute("AdvApi32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member AbortSystemShutdown : 
        ?machineName : string 
(* Defaults:
        let _machineName = defaultArg machineName "127.0.0.1"
*)
-> bool 

```


#### Parameters
&nbsp;<dl><dt>machineName (Optional)</dt><dd>Type: System.String<br />The network name of the computer where the shutdown is to be stopped. 

 If this parameter is a null reference (`Nothing` in Visual Basic) or an empty string, the function aborts the shutdown on the local computer.</dd></dl>

#### Return Value
Type: Boolean<br />`true` (`True` in Visual Basic) if the function succeeds, `false` (`False` in Visual Basic) otherwise.

## Remarks
<a href="https://msdn.microsoft.com/es-es/library/windows/desktop/aa376630%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/es-es/library/windows/desktop/aa376630%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />