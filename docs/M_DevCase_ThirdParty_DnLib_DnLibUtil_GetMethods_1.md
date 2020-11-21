# DnLibUtil.GetMethods Method (String, String)
 

Gets all the Methods defined in a existing Type inside a .NET assembly.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_DnLib">DevCase.ThirdParty.DnLib</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static ReadOnlyCollection<MethodDef> GetMethods(
	string assemblyPath,
	string typeName
)
```

**VB**<br />
``` VB
Public Shared Function GetMethods ( 
	assemblyPath As String,
	typeName As String
) As ReadOnlyCollection(Of MethodDef)
```

**VB Usage**<br />
``` VB Usage
Dim assemblyPath As String
Dim typeName As String
Dim returnValue As ReadOnlyCollection(Of MethodDef)

returnValue = DnLibUtil.GetMethods(assemblyPath, 
	typeName)
```

**C++**<br />
``` C++
public:
static ReadOnlyCollection<MethodDef^>^ GetMethods(
	String^ assemblyPath, 
	String^ typeName
)
```

**F#**<br />
``` F#
static member GetMethods : 
        assemblyPath : string * 
        typeName : string -> ReadOnlyCollection<MethodDef> 

```


#### Parameters
&nbsp;<dl><dt>assemblyPath</dt><dd>Type: System.String<br />The assembly filepath.</dd><dt>typeName</dt><dd>Type: System.String<br />The name of the type to find.</dd></dl>

#### Return Value
Type: ReadOnlyCollection(MethodDef)<br />A ReadOnlyCollection(T) containing the methods defined (including nested Types) inside a .NET assembly.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim methods As ReadOnlyCollection(Of MethodDef) = GetMethods("C:\Application.exe", "Main") ' Searchs a Class named "Main"

For Each method As MethodDef In methods

    ' If method contains instructions then...
    If method.HasBody Then

        Dim sb As New Global.System.Text.StringBuilder
        With sb
            .AppendLine(String.Format("Method Name: {0}", method.Name))
            .AppendLine()
            .AppendLine(String.Format("Method Signature: {0}", method.Signature.ToString()))
            .AppendLine()
            .AppendLine(String.Format("Method Instructions: {0}", Environment.NewLine &
                                      String.Join(Environment.NewLine, method.Body.Instructions)))
        End With

        MessageBox.Show(sb.ToString())

    End If ' method.HasBody

Next method
```


## See Also


#### Reference
<a href="T_DevCase_ThirdParty_DnLib_DnLibUtil">DnLibUtil Class</a><br /><a href="Overload_DevCase_ThirdParty_DnLib_DnLibUtil_GetMethods">GetMethods Overload</a><br /><a href="N_DevCase_ThirdParty_DnLib">DevCase.ThirdParty.DnLib Namespace</a><br />