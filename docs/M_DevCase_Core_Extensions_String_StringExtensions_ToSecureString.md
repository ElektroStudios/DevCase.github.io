# StringExtensions.ToSecureString Method 
 

Converts the source String to a SecureString.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_String">DevCase.Core.Extensions.String</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static SecureString ToSecureString(
	this string sender,
	bool readOnly = true
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function ToSecureString ( 
	sender As String,
	Optional readOnly As Boolean = true
) As SecureString
```

**VB Usage**<br />
``` VB Usage
Dim sender As String
Dim readOnly As Boolean
Dim returnValue As SecureString

returnValue = sender.ToSecureString(readOnly)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static SecureString^ ToSecureString(
	String^ sender, 
	bool readOnly = true
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member ToSecureString : 
        sender : string * 
        ?readOnly : bool 
(* Defaults:
        let _readOnly = defaultArg readOnly true
*)
-> SecureString 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.String<br />The source String.</dd><dt>readOnly (Optional)</dt><dd>Type: System.Boolean<br />\[Missing <param name="readOnly"/> documentation for "M:DevCase.Core.Extensions.String.StringExtensions.ToSecureString(System.String,System.Boolean)"\]</dd></dl>

#### Return Value
Type: SecureString<br />The resulting SecureString.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type String. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>ArgumentNullException</td><td>value</td></tr></table>

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim secstr As SecureString = "PASSWORD".ToSecureString()
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_String_StringExtensions">StringExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_String">DevCase.Core.Extensions.String Namespace</a><br />