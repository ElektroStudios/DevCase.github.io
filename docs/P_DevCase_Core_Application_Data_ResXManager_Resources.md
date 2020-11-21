# ResXManager.Resources Property 
 

Gets the resources contained in the .NET managed resource file.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_Data">DevCase.Core.Application.Data</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual IEnumerable<Resource> Resources { get; }
```

**VB**<br />
``` VB
Public Overridable ReadOnly Property Resources As IEnumerable(Of Resource)
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As ResXManager
Dim value As IEnumerable(Of Resource)

value = instance.Resources

```

**C++**<br />
``` C++
public:
virtual property IEnumerable<Resource^>^ Resources {
	IEnumerable<Resource^>^ get ();
}
```

**F#**<br />
``` F#
abstract Resources : IEnumerable<Resource> with get
override Resources : IEnumerable<Resource> with get
```


#### Property Value
Type: IEnumerable(<a href="T_DevCase_Core_Application_Data_Resource">Resource</a>)<br />The resources.

## See Also


#### Reference
<a href="T_DevCase_Core_Application_Data_ResXManager">ResXManager Class</a><br /><a href="N_DevCase_Core_Application_Data">DevCase.Core.Application.Data Namespace</a><br />