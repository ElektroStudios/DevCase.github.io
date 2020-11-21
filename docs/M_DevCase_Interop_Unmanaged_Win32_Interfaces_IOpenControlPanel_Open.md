# IOpenControlPanel.Open Method 
 

Opens the specified Control Panel item, optionally to a specific page.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[PreserveSigAttribute]
HResult Open(
	string name,
	string page,
	IntPtr punkSite
)
```

**VB**<br />
``` VB
<PreserveSigAttribute>
Function Open ( 
	name As String,
	page As String,
	punkSite As IntPtr
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim instance As IOpenControlPanel
Dim name As String
Dim page As String
Dim punkSite As IntPtr
Dim returnValue As HResult

returnValue = instance.Open(name, page, 
	punkSite)
```

**C++**<br />
``` C++
[PreserveSigAttribute]
HResult Open(
	String^ name, 
	String^ page, 
	IntPtr punkSite
)
```

**F#**<br />
``` F#
[<PreserveSigAttribute>]
abstract Open : 
        name : string * 
        page : string * 
        punkSite : IntPtr -> HResult 

```


#### Parameters
&nbsp;<dl><dt>name</dt><dd>Type: System.String<br />A pointer to the item's canonical name as a Unicode string. 

 This parameter is optional and can be a null reference (`Nothing` in Visual Basic). 

 If the calling application passes a null reference (`Nothing` in Visual Basic), then the Control Panel itself opens.</dd><dt>page</dt><dd>Type: System.String<br />A pointer to the name of the page within the item to display. 

 This string is appended to the end of the path for Shell folder Control Panel items or appended as a command-line parameter for Control Panel (.cpl) file items. 

 This parameter can be a null reference (`Nothing` in Visual Basic), in which case the first page is shown.</dd><dt>punkSite</dt><dd>Type: System.IntPtr<br />A pointer to the site for navigating in-frame for Shell folder Control Panel items. 

 This parameter can be Zero or a null reference (`Nothing` in Visual Basic).</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />If this method succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. Otherwise, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> error code.

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IOpenControlPanel">IOpenControlPanel Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />