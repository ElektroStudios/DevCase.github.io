# CommandLineValueParameterCollection.Item Property 
 

Gets or sets the <a href="T_DevCase_Core_Application_CommandLineValueParameter_1">CommandLineValueParameter(T)</a> that matches the specified key name.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application">DevCase.Core.Application</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public CommandLineValueParameter<IConvertible> this[
	string name
] { get; set; }
```

**VB**<br />
``` VB
Public Property Item ( 
	name As String
) As CommandLineValueParameter(Of IConvertible)
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As CommandLineValueParameterCollection
Dim name As String
Dim value As CommandLineValueParameter(Of IConvertible)

value = instance.Item(name)

instance.Item(name) = value
```

**C++**<br />
``` C++
public:
property CommandLineValueParameter<IConvertible^>^ Item[String^ name] {
	CommandLineValueParameter<IConvertible^>^ get (String^ name);
	void set (String^ name, CommandLineValueParameter<IConvertible^>^ value);
}
```

**F#**<br />
``` F#
member Item : CommandLineValueParameter<IConvertible> with get, set

```


#### Parameters
&nbsp;<dl><dt>name</dt><dd>Type: System.String<br />The parameter name.</dd></dl>

#### Property Value
Type: <a href="T_DevCase_Core_Application_CommandLineValueParameter_1">CommandLineValueParameter</a>(IConvertible)<br />The <a href="T_DevCase_Core_Application_CommandLineValueParameter_1">CommandLineValueParameter(T)</a>.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>NullReferenceException</td><td>Item not found with the specified name.</td></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Application_CommandLineValueParameterCollection">CommandLineValueParameterCollection Class</a><br /><a href="N_DevCase_Core_Application">DevCase.Core.Application Namespace</a><br />