# CommandLineValueParameter(*T*)&nbsp;Implicit Conversion (CommandLineValueParameter(Char) to CommandLineValueParameter(*T*))
 

Performs an implicit conversion from <a href="T_DevCase_Core_Application_CommandLineValueParameter_1">CommandLineValueParameter(T)</a> to <a href="T_DevCase_Core_Application_CommandLineValueParameter_1">CommandLineValueParameter(T)</a>.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Application">DevCase.Core.Application</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static implicit operator CommandLineValueParameter<T> (
	CommandLineValueParameter<char> cmd
)
```

**VB**<br />
``` VB
Public Shared Widening Operator CType ( 
	cmd As CommandLineValueParameter(Of Char)
) As CommandLineValueParameter(Of T)
```

**VB Usage**<br />
``` VB Usage
Dim input As CommandLineValueParameter(Of Char)
Dim output As CommandLineValueParameter(Of T)

output = CType(input, CommandLineValueParameter(Of T))
```

**C++**<br />
``` C++
static implicit operator CommandLineValueParameter<T>^ (
	CommandLineValueParameter<wchar_t>^ cmd
)
```

**F#**<br />
``` F#

```


#### Parameters
&nbsp;<dl><dt>cmd</dt><dd>Type: <a href="T_DevCase_Core_Application_CommandLineValueParameter_1">DevCase.Core.Application.CommandLineValueParameter</a>(Char)<br />The <a href="T_DevCase_Core_Application_CommandLineValueParameter_1">CommandLineValueParameter(T)</a> to convert.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Core_Application_CommandLineValueParameter_1">CommandLineValueParameter</a>(<a href="T_DevCase_Core_Application_CommandLineValueParameter_1">*T*</a>)<br />The resulting <a href="T_DevCase_Core_Application_CommandLineValueParameter_1">CommandLineValueParameter(T)</a>.

## See Also


#### Reference
<a href="T_DevCase_Core_Application_CommandLineValueParameter_1">CommandLineValueParameter(T) Class</a><br /><a href="Overload_DevCase_Core_Application_CommandLineValueParameter_1_op_Implicit">Implicit Overload</a><br /><a href="N_DevCase_Core_Application">DevCase.Core.Application Namespace</a><br />