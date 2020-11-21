# MessageExtensions.ToNativeMessage Method 
 

Converts a Message to a <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeMessage">NativeMessage</a>.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Message">DevCase.Core.Extensions.Message</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static NativeMessage ToNativeMessage(
	this Message msg
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function ToNativeMessage ( 
	msg As Message
) As NativeMessage
```

**VB Usage**<br />
``` VB Usage
Dim msg As Message
Dim returnValue As NativeMessage

returnValue = msg.ToNativeMessage()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static NativeMessage ToNativeMessage(
	Message msg
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member ToNativeMessage : 
        msg : Message -> NativeMessage 

```


#### Parameters
&nbsp;<dl><dt>msg</dt><dd>Type: System.Windows.Forms.Message<br />The source Message.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeMessage">NativeMessage</a><br />The resulting <a href="T_DevCase_Interop_Unmanaged_Win32_Structures_NativeMessage">NativeMessage</a>.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type Message. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Message_MessageExtensions">MessageExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_Message">DevCase.Core.Extensions.Message Namespace</a><br />