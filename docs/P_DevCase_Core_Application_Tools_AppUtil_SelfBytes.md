# AppUtil.SelfBytes Property 
 

Gets the bytes of the local file that points to the running assembly.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Tools">DevCase.Core.Application.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static byte[] SelfBytes { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property SelfBytes As Byte()
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As Byte()

value = AppUtil.SelfBytes

```

**C++**<br />
``` C++
public:
static property array<unsigned char>^ SelfBytes {
	array<unsigned char>^ get ();
}
```

**F#**<br />
``` F#
static member SelfBytes : byte[] with get

```


#### Property Value
Type: Byte[]<br />A Byte array containing the bytes of the local file that points to the running assembly.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim selfBytes As Byte() = SelfBytes()
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_Tools_AppUtil">AppUtil Class</a><br /><a href="N_DevCase_Core_Application_Tools">DevCase.Core.Application.Tools Namespace</a><br />