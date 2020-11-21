# SecureStringExtensions.ToUnsecureString Method 
 

Converts a SecureString to a common String.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_SecureString">DevCase.Core.Extensions.SecureString</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static string ToUnsecureString(
	this SecureString sender
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function ToUnsecureString ( 
	sender As SecureString
) As String
```

**VB Usage**<br />
``` VB Usage
Dim sender As SecureString
Dim returnValue As String

returnValue = sender.ToUnsecureString()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static String^ ToUnsecureString(
	SecureString^ sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member ToUnsecureString : 
        sender : SecureString -> string 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Security.SecureString<br />The source SecureString.</dd></dl>

#### Return Value
Type: String<br />The resulting String.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type SecureString. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim secStr As New SecureString
With secStr
    .AppendChar("q"c)
    .AppendChar("q"c)
    .AppendChar("w"c)
    .AppendChar("e"c)
    .AppendChar("r"c)
    .AppendChar("t"c)
    .AppendChar("y"c)
End With

MessageBox.Show(secStr.ToUnsecureString())
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_SecureString_SecureStringExtensions">SecureStringExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_SecureString">DevCase.Core.Extensions.SecureString Namespace</a><br />