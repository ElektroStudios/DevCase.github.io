# LicensingUtil.ProductKey Property 
 

Gets the Windows product key of the current operating system. 

 Note that the value could be a null reference (`Nothing` in Visual Basic) in case of the product key was completely removed from the Windows Registry (eg. using tools like `slmgr.vbs /cpky`).

**Namespace:**&nbsp;<a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string ProductKey { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property ProductKey As String
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As String

value = LicensingUtil.ProductKey

```

**C++**<br />
``` C++
public:
static property String^ ProductKey {
	String^ get ();
}
```

**F#**<br />
``` F#
static member ProductKey : string with get

```


#### Property Value
Type: String<br />The Windows product key, or a null reference (`Nothing` in Visual Basic) in case of the product key was completely removed from the Windows Registry (eg. using tools like `slmgr.vbs /cpky`).

## Remarks
Credits to: <a href="http://github.com/mrpeardotnet/WinProdKeyFinder" target="_blank">http://github.com/mrpeardotnet/WinProdKeyFinder</a>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim productKey As String = ProductKey()
Console.WriteLine(productKey)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Shell_Tools_LicensingUtil">LicensingUtil Class</a><br /><a href="N_DevCase_Core_Shell_Tools">DevCase.Core.Shell.Tools Namespace</a><br />