# HttpResponseExtensions.AddAttachment Method (HttpResponse, String, String, String)
 

Adds an attachment.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_HttpResponse">DevCase.Core.Extensions.HttpResponse</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static void AddAttachment(
	this HttpResponse sender,
	string localFilepath,
	string outputFileName,
	string contentType
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Sub AddAttachment ( 
	sender As HttpResponse,
	localFilepath As String,
	outputFileName As String,
	contentType As String
)
```

**VB Usage**<br />
``` VB Usage
Dim sender As HttpResponse
Dim localFilepath As String
Dim outputFileName As String
Dim contentType As String

sender.AddAttachment(localFilepath, 
	outputFileName, contentType)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static void AddAttachment(
	HttpResponse^ sender, 
	String^ localFilepath, 
	String^ outputFileName, 
	String^ contentType
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member AddAttachment : 
        sender : HttpResponse * 
        localFilepath : string * 
        outputFileName : string * 
        contentType : string -> unit 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: System.Web.HttpResponse<br />The source HttpResponse.</dd><dt>localFilepath</dt><dd>Type: System.String<br />The full path of the file to add as attachment.</dd><dt>outputFileName</dt><dd>Type: System.String<br />The filename to assign in the attachment.</dd><dt>contentType</dt><dd>Type: System.String<br />The MIME type name of the file.</dd></dl>

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type HttpResponse. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_HttpResponse_HttpResponseExtensions">HttpResponseExtensions Class</a><br /><a href="Overload_DevCase_Core_Extensions_HttpResponse_HttpResponseExtensions_AddAttachment">AddAttachment Overload</a><br /><a href="N_DevCase_Core_Extensions_HttpResponse">DevCase.Core.Extensions.HttpResponse Namespace</a><br />