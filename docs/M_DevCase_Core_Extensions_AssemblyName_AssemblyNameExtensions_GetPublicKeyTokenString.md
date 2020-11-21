# AssemblyNameExtensions.GetPublicKeyTokenString Method 
 

Gets a string representation of the public key token, which is the last 8 bytes of the SHA-1 hash of the public key under which the application or assembly is signed.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_AssemblyName">DevCase.Core.Extensions.AssemblyName</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static string GetPublicKeyTokenString(
	this AssemblyName sender
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function GetPublicKeyTokenString ( 
	sender As AssemblyName
) As String
```

**VB Usage**<br />
``` VB Usage
Dim sender As AssemblyName
Dim returnValue As String

returnValue = sender.GetPublicKeyTokenString()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static String^ GetPublicKeyTokenString(
	AssemblyName^ sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member GetPublicKeyTokenString : 
        sender : AssemblyName -> string 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Reflection.AssemblyName<br />The source AssemblyName.</dd></dl>

#### Return Value
Type: String<br />The resulting public key token, or an empty string if no public key is specified in the assembly.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type AssemblyName. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim asm As Assembly = Assembly.GetExecutingAssembly()
Dim asmName As AssemblyName = asm.GetName()
Dim publicKeyToken As String = GetPublicKeyTokenString(asmName)

Console.WriteLine(publicKeyToken)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_AssemblyName_AssemblyNameExtensions">AssemblyNameExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_AssemblyName">DevCase.Core.Extensions.AssemblyName Namespace</a><br />