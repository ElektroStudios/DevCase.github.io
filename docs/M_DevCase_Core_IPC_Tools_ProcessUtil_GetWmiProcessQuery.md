# ProcessUtil.GetWmiProcessQuery Method 
 

Performs a WMI query to Win32_Process class with the specified condition and returns the result.

**Namespace:**&nbsp;<a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public static ManagementObject[] GetWmiProcessQuery(
	KeyValuePair<string, string> condition
)
```

**VB**<br />
``` VB
Public Shared Function GetWmiProcessQuery ( 
	condition As KeyValuePair(Of String, String)
) As ManagementObject()
```

**VB Usage**<br />
``` VB Usage
Dim condition As KeyValuePair(Of String, String)
Dim returnValue As ManagementObject()

returnValue = ProcessUtil.GetWmiProcessQuery(condition)
```

**C++**<br />
``` C++
public:
static array<ManagementObject^>^ GetWmiProcessQuery(
	KeyValuePair<String^, String^> condition
)
```

**F#**<br />
``` F#
static member GetWmiProcessQuery : 
        condition : KeyValuePair<string, string> -> ManagementObject[] 

```


#### Parameters
&nbsp;<dl><dt>condition</dt><dd>Type: System.Collections.Generic.KeyValuePair(String, String)<br />The WHERE condition to use in the SELECT query.</dd></dl>

#### Return Value
Type: ManagementObject[]<br />The query result.

## Remarks
This is useful for example to get information of a 64-Bit process from a 32-Bit .NET assembly.

## Examples
This is a code example. 
**VB**<br />
``` VB
Dim condition As New KeyValuePair(Of String, String)("Name", "notepad.exe")

For Each mo As ManagementObject In GetWmiProcessQuery(condition)
    MessageBox.Show(DirectCast(mo.Properties("ExecutablePath").Value, String))
Next mo
```


## See Also


#### Reference
<a href="T_DevCase_Core_IPC_Tools_ProcessUtil">ProcessUtil Class</a><br /><a href="N_DevCase_Core_IPC_Tools">DevCase.Core.IPC.Tools Namespace</a><br />