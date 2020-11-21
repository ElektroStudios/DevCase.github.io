# IOpenControlPanel.GetPath Method 
 

Gets the path of a specified Control Panel item.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[PreserveSigAttribute]
HResult GetPath(
	string name,
	StringBuilder path,
	int bufferSize
)
```

**VB**<br />
``` VB
<PreserveSigAttribute>
Function GetPath ( 
	name As String,
	path As StringBuilder,
	bufferSize As Integer
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim instance As IOpenControlPanel
Dim name As String
Dim path As StringBuilder
Dim bufferSize As Integer
Dim returnValue As HResult

returnValue = instance.GetPath(name, path, 
	bufferSize)
```

**C++**<br />
``` C++
[PreserveSigAttribute]
HResult GetPath(
	String^ name, 
	StringBuilder^ path, 
	int bufferSize
)
```

**F#**<br />
``` F#
[<PreserveSigAttribute>]
abstract GetPath : 
        name : string * 
        path : StringBuilder * 
        bufferSize : int -> HResult 

```


#### Parameters
&nbsp;<dl><dt>name</dt><dd>Type: System.String<br />A pointer to the item's canonical name or its GUID. 

 This value can be a null reference (`Nothing` in Visual Basic).</dd><dt>path</dt><dd>Type: System.Text.StringBuilder<br />When this method returns, contains the path of the specified Control Panel item as a Unicode string.</dd><dt>bufferSize</dt><dd>Type: System.Int32<br />The size of the buffer pointed to by *path* parameter.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />If this method succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. Otherwise, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> error code.

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IOpenControlPanel">IOpenControlPanel Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />