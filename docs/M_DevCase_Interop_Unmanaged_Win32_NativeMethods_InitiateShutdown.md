# NativeMethods.InitiateShutdown Method 
 

Initiates a shutdown and restart of the specified computer, and restarts any applications that have been registered for restart.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("AdvApi32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static uint InitiateShutdown(
	string machineName,
	string message,
	int gracePeriod,
	uint shutdownFlags,
	uint reason
)
```

**VB**<br />
``` VB
<DllImportAttribute("AdvApi32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function InitiateShutdown ( 
	machineName As String,
	message As String,
	gracePeriod As Integer,
	shutdownFlags As UInteger,
	reason As UInteger
) As UInteger
```

**VB Usage**<br />
``` VB Usage
Dim machineName As String
Dim message As String
Dim gracePeriod As Integer
Dim shutdownFlags As UInteger
Dim reason As UInteger
Dim returnValue As UInteger

returnValue = NativeMethods.InitiateShutdown(machineName, 
	message, gracePeriod, shutdownFlags, 
	reason)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"AdvApi32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static unsigned int InitiateShutdown(
	String^ machineName, 
	String^ message, 
	int gracePeriod, 
	unsigned int shutdownFlags, 
	unsigned int reason
)
```

**F#**<br />
``` F#
[<DllImportAttribute("AdvApi32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member InitiateShutdown : 
        machineName : string * 
        message : string * 
        gracePeriod : int * 
        shutdownFlags : uint32 * 
        reason : uint32 -> uint32 

```


#### Parameters
&nbsp;<dl><dt>machineName</dt><dd>Type: System.String<br />The name of the computer to be shut down. 

 If the value of this parameter is a null reference (`Nothing` in Visual Basic), the local computer is shut down. This parameter can be an addres, for example: `127.0.0.1`</dd><dt>message</dt><dd>Type: System.String<br />The message to be displayed in the interactive shutdown dialog box.</dd><dt>gracePeriod</dt><dd>Type: System.Int32<br />The number of seconds to wait before shutting down the computer. 

 If the value of this parameter is zero, the computer is shut down immediately. This value is limited to `MAX_SHUTDOWN_TIMEOUT`. 

 If the value of this parameter is greater than zero, and the *shutdownFlags* parameter specifies the flag `GRACE_OVERRIDE`, the function fails and returns the error code `ERROR_BAD_ARGUMENTS`.</dd><dt>shutdownFlags</dt><dd>Type: System.UInt32<br />Specifies options for the shutdown.</dd><dt>reason</dt><dd>Type: System.UInt32<br />The reason for initiating the shutdown. 

 If this parameter is zero, the default is an undefined shutdown that is logged as "No title for this reason could be found". By default, it is also an 'unplanned' shutdown.</dd></dl>

#### Return Value
Type: UInt32<br />If the function succeeds, it returns `ERROR_SUCCESS`.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/aa376872%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/aa376872%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />