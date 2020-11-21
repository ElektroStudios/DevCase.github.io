# JunkCodeUtil.CreateJunkField(*T*) Method 
 

Generates a junk-code field of the given Type written in the specified .NET language.

**Namespace:**&nbsp;<a href="N_DevCase_Core_Cryptography_Tools">DevCase.Core.Cryptography.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static string CreateJunkField<T>(
	NetSyntaxStyle syntax
)

```

**VB**<br />
``` VB
Public Shared Function CreateJunkField(Of T) ( 
	syntax As NetSyntaxStyle
) As String
```

**VB Usage**<br />
``` VB Usage
Dim syntax As NetSyntaxStyle
Dim returnValue As String

returnValue = JunkCodeUtil.CreateJunkField(syntax)
```

**C++**<br />
``` C++
public:
generic<typename T>
static String^ CreateJunkField(
	NetSyntaxStyle syntax
)
```

**F#**<br />
``` F#
static member CreateJunkField : 
        syntax : NetSyntaxStyle -> string 

```


#### Parameters
&nbsp;<dl><dt>syntax</dt><dd>Type: <a href="T_DevCase_Interop_Managed_NetSyntaxStyle">DevCase.Interop.Managed.NetSyntaxStyle</a><br />The syntax style to use.</dd></dl>

#### Type Parameters
&nbsp;<dl><dt>T</dt><dd>The Type of the Field.</dd></dl>

#### Return Value
Type: String<br />The resulting Field.

## Exceptions
&nbsp;<table><tr><th>Exception</th><th>Condition</th></tr><tr><td>NotSupportedException</td><td /></tr></table>

## See Also


#### Reference
<a href="T_DevCase_Core_Cryptography_Tools_JunkCodeUtil">JunkCodeUtil Class</a><br /><a href="N_DevCase_Core_Cryptography_Tools">DevCase.Core.Cryptography.Tools Namespace</a><br />