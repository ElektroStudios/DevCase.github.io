# SecureStringExtensions.AppendChars Method 
 

Appends the specified character to the end of the source SecureString.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_SecureString">DevCase.Core.Extensions.SecureString</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static void AppendChars(
	this SecureString sender,
	char[] chars
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Sub AppendChars ( 
	sender As SecureString,
	chars As Char()
)
```

**VB Usage**<br />
``` VB Usage
Dim sender As SecureString
Dim chars As Char()

sender.AppendChars(chars)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static void AppendChars(
	SecureString^ sender, 
	array<wchar_t>^ chars
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member AppendChars : 
        sender : SecureString * 
        chars : char[] -> unit 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Security.SecureString<br />The source SecureString.</dd><dt>chars</dt><dd>Type: System.Char[]<br />The characters to append.</dd></dl>

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type SecureString. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim secStr As New SecureString
secStr.AppendChars("qwerty".ToCharArray())

MessageBox.Show(secStr.ToUnsecureString())
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_SecureString_SecureStringExtensions">SecureStringExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_SecureString">DevCase.Core.Extensions.SecureString Namespace</a><br />