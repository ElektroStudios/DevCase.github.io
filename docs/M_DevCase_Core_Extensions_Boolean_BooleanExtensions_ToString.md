# BooleanExtensions.ToString Method 
 

Returns a custom string representation for a the Boolean value.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Boolean">DevCase.Core.Extensions.Boolean</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static string ToString(
	this bool sender,
	string iftrue,
	string ifFalse
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function ToString ( 
	sender As Boolean,
	iftrue As String,
	ifFalse As String
) As String
```

**VB Usage**<br />
``` VB Usage
Dim sender As Boolean
Dim iftrue As String
Dim ifFalse As String
Dim returnValue As String

returnValue = sender.ToString(iftrue, 
	ifFalse)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static String^ ToString(
	bool sender, 
	String^ iftrue, 
	String^ ifFalse
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member ToString : 
        sender : bool * 
        iftrue : string * 
        ifFalse : string -> string 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Boolean<br />The source Boolean.</dd><dt>iftrue</dt><dd>Type: System.String<br />A string representation to return if the source Boolean is `true` (`True` in Visual Basic).</dd><dt>ifFalse</dt><dd>Type: System.String<br />A string representation to return if the source Boolean is `false` (`False` in Visual Basic).</dd></dl>

#### Return Value
Type: String<br />Returns *iftrue* if the Boolean value is `true` (`True` in Visual Basic); or the *ifFalse* if the Boolean value is `false` (`False` in Visual Basic)

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Boolean. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim str As String = (True).ToString(iftrue:="Yes", ifFalse:="No")
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Boolean_BooleanExtensions">BooleanExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_Boolean">DevCase.Core.Extensions.Boolean Namespace</a><br />