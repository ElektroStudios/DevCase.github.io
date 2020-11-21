# IActiveDesktop.GetWallpaper Method 
 

Gets the current wallpaper.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[PreserveSigAttribute]
int GetWallpaper(
	StringBuilder buffer,
	int bufferSize,
	int reserved
)
```

**VB**<br />
``` VB
<PreserveSigAttribute>
Function GetWallpaper ( 
	buffer As StringBuilder,
	bufferSize As Integer,
	reserved As Integer
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim instance As IActiveDesktop
Dim buffer As StringBuilder
Dim bufferSize As Integer
Dim reserved As Integer
Dim returnValue As Integer

returnValue = instance.GetWallpaper(buffer, 
	bufferSize, reserved)
```

**C++**<br />
``` C++
[PreserveSigAttribute]
int GetWallpaper(
	StringBuilder^ buffer, 
	int bufferSize, 
	int reserved
)
```

**F#**<br />
``` F#
[<PreserveSigAttribute>]
abstract GetWallpaper : 
        buffer : StringBuilder * 
        bufferSize : int * 
        reserved : int -> int 

```


#### Parameters
&nbsp;<dl><dt>buffer</dt><dd>Type: System.Text.StringBuilder<br />When this method returns, contains the file name of the wallpaper.</dd><dt>bufferSize</dt><dd>Type: System.Int32<br />The size of *buffer* value, in characters.</dd><dt>reserved</dt><dd>Type: System.Int32<br />Reserved. Must be set to zero.</dd></dl>

#### Return Value
Type: Int32<br />If the function succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>, otherwise, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> error code.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/bb776355%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/bb776355%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IActiveDesktop">IActiveDesktop Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />