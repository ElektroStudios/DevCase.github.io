# ConsoleUtil.JoinArguments Method 
 

Returns a single string representation of the command-line arguments for the current process.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application_UserInterface_Tools_Console">DevCase.Core.Application.UserInterface.Tools.Console</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string JoinArguments(
	IEnumerable<string> args = null,
	char delimiter = ''
)
```

**VB**<br />
``` VB
Public Shared Function JoinArguments ( 
	Optional args As IEnumerable(Of String) = Nothing,
	Optional delimiter As Char = ""C
) As String
```

**VB Usage**<br />
``` VB Usage
Dim args As IEnumerable(Of String)
Dim delimiter As Char
Dim returnValue As String

returnValue = ConsoleUtil.JoinArguments(args, 
	delimiter)
```

**C++**<br />
``` C++
public:
static String^ JoinArguments(
	IEnumerable<String^>^ args = nullptr, 
	wchar_t delimiter = L''
)
```

**F#**<br />
``` F#
static member JoinArguments : 
        ?args : IEnumerable<string> * 
        ?delimiter : char 
(* Defaults:
        let _args = defaultArg args null
        let _delimiter = defaultArg delimiter ''
*)
-> string 

```


#### Parameters
&nbsp;<dl><dt>args (Optional)</dt><dd>Type: System.Collections.Generic.IEnumerable(String)<br />A custom collection of arguments to examine.</dd><dt>delimiter (Optional)</dt><dd>Type: System.Char<br />\[Missing <param name="delimiter"/> documentation for "M:DevCase.Core.Application.UserInterface.Tools.Console.ConsoleUtil.JoinArguments(System.Collections.Generic.IEnumerable{System.String},System.Char)"\]</dd></dl>

#### Return Value
Type: String<br />\[Missing <returns> documentation for "M:DevCase.Core.Application.UserInterface.Tools.Console.ConsoleUtil.JoinArguments(System.Collections.Generic.IEnumerable{System.String},System.Char)"\]

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim args As String = JoinArguments(, ";"c)
```


## See Also


#### Reference
<a href="T_DevCase_Core_Application_UserInterface_Tools_Console_ConsoleUtil">ConsoleUtil Class</a><br /><a href="N_DevCase_Core_Application_UserInterface_Tools_Console">DevCase.Core.Application.UserInterface.Tools.Console Namespace</a><br />