# SecureStringExtensions.AppendString Method 
 

Appends a string to the end of the source SecureString.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_SecureString">DevCase.Core.Extensions.SecureString</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static void AppendString(
	this SecureString sender,
	string str
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Sub AppendString ( 
	sender As SecureString,
	str As String
)
```

**VB Usage**<br />
``` VB Usage
Dim sender As SecureString
Dim str As String

sender.AppendString(str)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static void AppendString(
	SecureString^ sender, 
	String^ str
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member AppendString : 
        sender : SecureString * 
        str : string -> unit 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Security.SecureString<br />The source SecureString.</dd><dt>str</dt><dd>Type: System.String<br />The string to append.</dd></dl>

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type SecureString. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim secStr As New SecureString
secStr.AppendString("qwerty")

MessageBox.Show(secStr.ToUnsecureString())
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_SecureString_SecureStringExtensions">SecureStringExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_SecureString">DevCase.Core.Extensions.SecureString Namespace</a><br />