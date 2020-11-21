# NativeMethods.SetWindowTheme Method 
 

Causes a window to use a different set of visual style information than its class normally uses.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("UxTheme.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)]
public static HResult SetWindowTheme(
	IntPtr hWnd,
	string subAppName,
	string subIdList
)
```

**VB**<br />
``` VB
<DllImportAttribute("UxTheme.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true>]
Public Shared Function SetWindowTheme ( 
	hWnd As IntPtr,
	subAppName As String,
	subIdList As String
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim hWnd As IntPtr
Dim subAppName As String
Dim subIdList As String
Dim returnValue As HResult

returnValue = NativeMethods.SetWindowTheme(hWnd, 
	subAppName, subIdList)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"UxTheme.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)]
static HResult SetWindowTheme(
	IntPtr hWnd, 
	String^ subAppName, 
	String^ subIdList
)
```

**F#**<br />
``` F#
[<DllImportAttribute("UxTheme.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)>]
static member SetWindowTheme : 
        hWnd : IntPtr * 
        subAppName : string * 
        subIdList : string -> HResult 

```


#### Parameters
&nbsp;<dl><dt>hWnd</dt><dd>Type: System.IntPtr<br />Handle to the window whose visual style information is to be changed.</dd><dt>subAppName</dt><dd>Type: System.String<br />Pointer to a string that contains the application name to use in place of the calling application's name. 

 If this parameter is a null reference (`Nothing` in Visual Basic), the calling application's name is used.</dd><dt>subIdList</dt><dd>Type: System.String<br />Pointer to a string that contains a semicolon-separated list of CLSID names to use in place of the actual list passed by the window's class. 

 If this parameter is a null reference (`Nothing` in Visual Basic), the ID list from the calling class is used.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />If this function succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. Otherwise, it returns a different error code.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/bb759827(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/bb759827(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />