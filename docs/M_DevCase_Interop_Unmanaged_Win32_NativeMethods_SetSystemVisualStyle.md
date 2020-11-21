# NativeMethods.SetSystemVisualStyle Method 
 

Sets the system visual theme.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("UxTheme.dll", EntryPoint = "#65", CharSet = CharSet.Unicode, 
	BestFitMapping = false, ThrowOnUnmappableChar = true)]
public static int SetSystemVisualStyle(
	string themeFileName,
	string colorName,
	string sizeName,
	int reserved
)
```

**VB**<br />
``` VB
<DllImportAttribute("UxTheme.dll", EntryPoint := "#65", CharSet := CharSet.Unicode, 
	BestFitMapping := false, ThrowOnUnmappableChar := true>]
Public Shared Function SetSystemVisualStyle ( 
	themeFileName As String,
	colorName As String,
	sizeName As String,
	reserved As Integer
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim themeFileName As String
Dim colorName As String
Dim sizeName As String
Dim reserved As Integer
Dim returnValue As Integer

returnValue = NativeMethods.SetSystemVisualStyle(themeFileName, 
	colorName, sizeName, reserved)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"UxTheme.dll", EntryPoint = L"#65", CharSet = CharSet::Unicode, 
	BestFitMapping = false, ThrowOnUnmappableChar = true)]
static int SetSystemVisualStyle(
	String^ themeFileName, 
	String^ colorName, 
	String^ sizeName, 
	int reserved
)
```

**F#**<br />
``` F#
[<DllImportAttribute("UxTheme.dll", EntryPoint = "#65", CharSet = CharSet.Unicode, 
	BestFitMapping = false, ThrowOnUnmappableChar = true)>]
static member SetSystemVisualStyle : 
        themeFileName : string * 
        colorName : string * 
        sizeName : string * 
        reserved : int -> int 

```


#### Parameters
&nbsp;<dl><dt>themeFileName</dt><dd>Type: System.String<br />The theme filepath (themme.msstyles).</dd><dt>colorName</dt><dd>Type: System.String<br />The color scheme name.</dd><dt>sizeName</dt><dd>Type: System.String<br />The size name.</dd><dt>reserved</dt><dd>Type: System.Int32<br />Reserved parameter by the system.</dd></dl>

#### Return Value
Type: Int32<br />\[Missing <returns> documentation for "M:DevCase.Interop.Unmanaged.Win32.NativeMethods.SetSystemVisualStyle(System.String,System.String,System.String,System.Int32)"\]

## Remarks
<a href="http://www.pinvoke.net/default.aspx/uxtheme/SetSystemVisualStyle.html" target="_blank">http://www.pinvoke.net/default.aspx/uxtheme/SetSystemVisualStyle.html</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />