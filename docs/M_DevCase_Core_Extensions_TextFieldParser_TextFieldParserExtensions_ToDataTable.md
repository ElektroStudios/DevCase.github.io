# TextFieldParserExtensions.ToDataTable Method 
 

Converts the source TextFieldParser to DataTable.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Extensions_TextFieldParser">DevCase.Core.Extensions.TextFieldParser</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[EditorBrowsableAttribute(EditorBrowsableState.Always)]
public static DataTable ToDataTable(
	this TextFieldParser sender,
	bool useFirstRowAsColumns
)
```

**VB**<br />
``` VB
<ExtensionAttribute>
<EditorBrowsableAttribute(EditorBrowsableState.Always)>
Public Shared Function ToDataTable ( 
	sender As TextFieldParser,
	useFirstRowAsColumns As Boolean
) As DataTable
```

**VB Usage**<br />
``` VB Usage
Dim sender As TextFieldParser
Dim useFirstRowAsColumns As Boolean
Dim returnValue As DataTable

returnValue = sender.ToDataTable(useFirstRowAsColumns)
```

**C++**<br />
``` C++
public:
[ExtensionAttribute]
[EditorBrowsableAttribute(EditorBrowsableState::Always)]
static DataTable^ ToDataTable(
	TextFieldParser^ sender, 
	bool useFirstRowAsColumns
)
```

**F#**<br />
``` F#
[<ExtensionAttribute>]
[<EditorBrowsableAttribute(EditorBrowsableState.Always)>]
static member ToDataTable : 
        sender : TextFieldParser * 
        useFirstRowAsColumns : bool -> DataTable 

```


#### Parameters
&nbsp;<dl><dt>sender</dt><dd>Type: Microsoft.VisualBasic.FileIO.TextFieldParser<br />The source TextFieldParser.</dd><dt>useFirstRowAsColumns</dt><dd>Type: System.Boolean<br />If set to `true` (`True` in Visual Basic), use the items of the first row of the source TextFieldParser to create the columns of the resulting DataTable.</dd></dl>

#### Return Value
Type: DataTable<br />The resulting DataTable.

#### Usage Note
In Visual Basic and C#, you can call this method as an instance method on any object of type TextFieldParser. When you use instance method syntax to call this method, omit the first parameter. For more information, see <a href="https://docs.microsoft.com/dotnet/visual-basic/programming-guide/language-features/procedures/extension-methods">Extension Methods (Visual Basic)</a> or <a href="https://docs.microsoft.com/dotnet/csharp/programming-guide/classes-and-structs/extension-methods">Extension Methods (C# Programming Guide)</a>.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim csvTable As New DataTable()

Dim csvText As String =
    
         Name; Last Name; Age
         Michael; Johnson Phillips; 26
         William; Lee Williams; 34
         Susan; Parker Evans; 32
         Matilda; Garcia Martinez; 28
    .Value

Using csvReader As New StringReader(csvText),
      csvParser As New TextFieldParser(csvReader) With {
      .Delimiters = {";"c},
      .HasFieldsEnclosedInQuotes = False,
      .TextFieldType = FieldType.Delimited
}

    csvTable = TextFieldParserExtensions.ToDataTable(csvParser, useFirstRowAsColumns:=True)
End Using

Me.DataGridView1.DataSource = csvTable
```


## See Also


#### Reference
<a href="T_DevCase_Core_Extensions_TextFieldParser_TextFieldParserExtensions">TextFieldParserExtensions Class</a><br /><a href="N_DevCase_Core_Extensions_TextFieldParser">DevCase.Core.Extensions.TextFieldParser Namespace</a><br />