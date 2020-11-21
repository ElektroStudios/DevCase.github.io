# ByteExtensions.ReadUntilFirstNullByte Method (Byte[])
 

Reads the specified bytes until the first null (zero) byte is found, or until the end, in case of a null byte is not found.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Byte">DevCase.Core.Extensions.Byte</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static byte[] ReadUntilFirstNullByte(
	this byte[] sender
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function ReadUntilFirstNullByte ( 
	sender As Byte()
) As Byte()
```

**VB Usage**<br />
``` VB Usage
Dim sender As Byte()
Dim returnValue As Byte()

returnValue = sender.ReadUntilFirstNullByte()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static array<unsigned char>^ ReadUntilFirstNullByte(
	array<unsigned char>^ sender
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member ReadUntilFirstNullByte : 
        sender : byte[] -> byte[] 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Byte[]<br />The byte data to read.</dd></dl>

#### Return Value
Type: Byte[]<br />The bytes read until the first null byte found, or until the end, in case of a null byte is not found.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type . When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim rawData As Byte() = New Byte() {72, 101, 108, 108, 111, 32, 87, 111, 114, 108, 100, 33, 0, 0, 0} ' "Hello World!\0\0\0"
Dim readable As Byte() = ReadUntilFirstNullByte(rawData)
Dim str As String = Encoding.ASCII.GetString(readable)
MsgBox(String.Format("""{0}""", str))
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Byte_ByteExtensions">ByteExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_Byte_ByteExtensions_ReadUntilFirstNullByte">ReadUntilFirstNullByte Overload</a><br /><a href="N_DevCase_Core_Extensions_Byte">DevCase.Core.Extensions.Byte Namespace</a><br />