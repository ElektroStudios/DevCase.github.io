# LicensingUtil.ProductId Property 
 

Gets the Windows product identifier of the current operating system.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string ProductId { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property ProductId As String
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As String

value = LicensingUtil.ProductId

```

**C++**<br />
``` C++
public:
static property String^ ProductId {
	String^ get ();
}
```

**F#**<br />
``` F#
static member ProductId : string with get

```


#### Property Value
Type: String<br />The Windows product identifier.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim productId As String = ProductId()
Console.WriteLine(productId)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_LicensingUtil">LicensingUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />