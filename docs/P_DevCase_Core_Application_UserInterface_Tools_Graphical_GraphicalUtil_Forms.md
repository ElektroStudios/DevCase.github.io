# GraphicalUtil.Forms Property 
 

Gets a collection that contains all the declared Forms of the current assembly.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface_Tools_Graphical">DevCase.Core.Application.UserInterface.Tools.Graphical</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static IEnumerable<Form> Forms { get; }
```

**VB**<br />
``` VB
Public Shared ReadOnly Property Forms As IEnumerable(Of Form)
	Get
```

**VB Usage**<br />
``` VB Usage
Dim value As IEnumerable(Of Form)

value = GraphicalUtil.Forms

```

**C++**<br />
``` C++
public:
static property IEnumerable<Form^>^ Forms {
	IEnumerable<Form^>^ get ();
}
```

**F#**<br />
``` F#
static member Forms : IEnumerable<Form> with get

```


#### Property Value
Type: IEnumerable(Form)<br />A collection that contains all the declared Forms of the current assembly.

## Examples
This is a code example. 
**VB**<br />
``` VB
For Each f As Form In Forms
    Console.WriteLine(f.Name)
Next
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_Tools_Graphical_GraphicalUtil">GraphicalUtil Class</a><br /><a href="N_DevCase_Core_Application_UserInterface_Tools_Graphical">DevCase.Core.Application.UserInterface.Tools.Graphical Namespace</a><br />