# ConsoleProgressBar.ProgressTextFormat Property 
 

Gets or sets the format of the progress text, where: 

 {0} = Percentage Value 

 {1} = Current Value 

 {2} = Maximum Value 

 Default value is: "{0}%"

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public string ProgressTextFormat { get; set; }
```

**VB**<br />
``` VB
Public Property ProgressTextFormat As String
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As ConsoleProgressBar
Dim value As String

value = instance.ProgressTextFormat

instance.ProgressTextFormat = value
```

**C++**<br />
``` C++
public:
property String^ ProgressTextFormat {
	String^ get ();
	void set (String^ value);
}
```

**F#**<br />
``` F#
member ProgressTextFormat : string with get, set

```


#### Property Value
Type: String<br />The format of the percentage string.

## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_ConsoleProgressBar">ConsoleProgressBar Class</a><br /><a href="N_DevCase_Core_Application_UserInterface">DevCase.Core.Application.UserInterface Namespace</a><br />