# VolumeUtil.SerialNumber Property 
 

Gets the serial number, in Hexadecimal, that the operating system assigned to the current volume.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string SerialNumber { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property SerialNumber As String
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As String

value = VolumeUtil.SerialNumber

```

**C++**<br />
``` C++
public:
static property String^ SerialNumber {
	String^ get ();
}
```

**F#**<br />
``` F#
static member SerialNumber : string with get

```


#### Property Value
Type: String<br />The serial number, in Hexadecimal, that the operating system assigned to the current volume, or a null reference (`Nothing` in Visual Basic) in case of the function failed to retrieve the value.

## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_VolumeUtil">VolumeUtil Class</a><br /><a href="Overload_DevCase_Core_Shell_Tools_VolumeUtil_SerialNumber">SerialNumber Overload</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />