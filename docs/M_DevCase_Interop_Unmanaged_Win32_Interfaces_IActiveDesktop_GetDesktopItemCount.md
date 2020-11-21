# IActiveDesktop.GetDesktopItemCount Method 
 

Gets a count of the desktop items.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[PreserveSigAttribute]
int GetDesktopItemCount(
	out int refCount,
	int reserved
)
```

**VB**<br />
``` VB
<PreserveSigAttribute>
Function GetDesktopItemCount ( 
	<OutAttribute> ByRef refCount As Integer,
	reserved As Integer
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim instance As IActiveDesktop
Dim refCount As Integer
Dim reserved As Integer
Dim returnValue As Integer

returnValue = instance.GetDesktopItemCount(refCount, 
	reserved)
```

**C++**<br />
``` C++
[PreserveSigAttribute]
int GetDesktopItemCount(
	[OutAttribute] int% refCount, 
	int reserved
)
```

**F#**<br />
``` F#
[<PreserveSigAttribute>]
abstract GetDesktopItemCount : 
        refCount : int byref * 
        reserved : int -> int 

```


#### Parameters
&nbsp;<dl><dt>refCount</dt><dd>Type: System.Int32<br />A pointer to an int value that, when this method returns successfully, contains the count..</dd><dt>reserved</dt><dd>Type: System.Int32<br />Reserved. Must be set to zero.</dd></dl>

#### Return Value
Type: Int32<br />If the function succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>, otherwise, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> error code.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/bb776352%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/bb776352%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IActiveDesktop">IActiveDesktop Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />