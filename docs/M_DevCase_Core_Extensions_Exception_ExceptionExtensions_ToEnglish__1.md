# ExceptionExtensions.ToEnglish(*T*) Method 
 

Converts the message of a Exception to English language.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_Exception">DevCase.Core.Extensions.Exception</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static string ToEnglish<T>(
	this T ex
)
where T : Exception

```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function ToEnglish(Of T As Exception) ( 
	ex As T
) As String
```

**VB Usage**<br />
``` VB Usage
Dim ex As T
Dim returnValue As String

returnValue = ex.ToEnglish()
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
generic<typename T>
where T : Exception
static String^ ToEnglish(
	T ex
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member ToEnglish : 
        ex : 'T -> string  when 'T : Exception

```


#### Parameters
&nbsp;<dl><dt>ex</dt><dd>Type: *T*<br />An Exception that contains an exception message in a non-english language.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>\[Missing <typeparam name="T"/> documentation for "M:DevCase.Core.Extensions.Exception.ExceptionExtensions.ToEnglish``1(``0)"\]</dd></dl>

#### Return Value
Type: String<br />The exception message in English language.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type . When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Try
    Throw New FileNotFoundException

Catch ex As FileNotFoundException
    Dim message As String = ex.ToEnglish

End Try
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_Exception_ExceptionExtensions">ExceptionExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_Exception">DevCase.Core.Extensions.Exception Namespace</a><br />