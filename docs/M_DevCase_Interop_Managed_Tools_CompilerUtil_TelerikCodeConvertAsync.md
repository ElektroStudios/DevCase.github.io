# CompilerUtil.TelerikCodeConvertAsync Method 
 

Asynchronously converts source-codes between C# and Visual Basic.NET languages. 

 This feature is powered by Telerik's Code converter web service (<a href="http://converter.telerik.com/service.asmx" target="_blank">http://converter.telerik.com/service.asmx</a>).

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Managed_Tools">DevCase.Interop.Managed.Tools</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static Task<string> TelerikCodeConvertAsync(
	TelerikCodeConverterMethod converterMethod,
	string sourceCode
)
```

**VB**<br />
``` VB
Public Shared Function TelerikCodeConvertAsync ( 
	converterMethod As TelerikCodeConverterMethod,
	sourceCode As String
) As Task(Of String)
```

**VB Usage**<br />
``` VB Usage
Dim converterMethod As TelerikCodeConverterMethod
Dim sourceCode As String
Dim returnValue As Task(Of String)

returnValue = CompilerUtil.TelerikCodeConvertAsync(converterMethod, 
	sourceCode)
```

**C++**<br />
``` C++
public:
static Task<String^>^ TelerikCodeConvertAsync(
	TelerikCodeConverterMethod converterMethod, 
	String^ sourceCode
)
```

**F#**<br />
``` F#
static member TelerikCodeConvertAsync : 
        converterMethod : TelerikCodeConverterMethod * 
        sourceCode : string -> Task<string> 

```


#### Parameters
&nbsp;<dl><dt>converterMethod</dt><dd>Type: <a href="T_DevCase_Interop_Managed_TelerikCodeConverterMethod">DevCase.Interop.Managed.TelerikCodeConverterMethod</a><br />The conversion method, that is, VB.NET to C#, or C# to VB.NET.</dd><dt>sourceCode</dt><dd>Type: System.String<br />The source-code to convert.</dd></dl>

#### Return Value
Type: Task(String)<br />The resulting source-code converted in the specified language by *converterMethod*.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>InvalidEnumArgumentException</td><td /></tr></table>

## Remarks
<a href="http://converter.telerik.com/service.asmx" target="_blank">http://converter.telerik.com/service.asmx</a>

## Examples
This is a code example to convert C# code to VB.NET. 
**VB**<br />
``` VB
Dim sourceCode As String = string str = "Hello World";.Value
Dim result As String = Await TelerikCodeConvertAsync(TelerikCodeConverterMethod.CSharpToVisualBasic, sourceCode)
Console.WriteLine(result)
```


## Examples
This is a code example to convert VB.NET code to C#. 
**VB**<br />
``` VB
Dim sourceCode As String = Dim str As String = "Hello World".Value
Dim result As String = Await TelerikCodeConvertAsync(TelerikCodeConverterMethod.VisualBasicToCSharp, sourceCode)
Console.WriteLine(result)
```


## See Also


#### Reference
<a href="T_DevCase_Interop_Managed_Tools_CompilerUtil">CompilerUtil Class</a><br /><a href="N_DevCase_Interop_Managed_Tools">DevCase.Interop.Managed.Tools Namespace</a><br />