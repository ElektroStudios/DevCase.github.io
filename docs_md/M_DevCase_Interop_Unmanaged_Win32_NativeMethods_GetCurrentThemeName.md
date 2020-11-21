# NativeMethods.GetCurrentThemeName Method 
 

Retrieves the name of the current visual style, and optionally retrieves the color scheme name and size name.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("UxTheme.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)]
public static int GetCurrentThemeName(
	StringBuilder themeFileName,
	int maxNameChars,
	StringBuilder colorBuffer,
	int maxColorChars,
	StringBuilder sizeBuffer,
	int maxSizeChars
)
```

**VB**<br />
``` VB
<DllImportAttribute("UxTheme.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true>]
Public Shared Function GetCurrentThemeName ( 
	themeFileName As StringBuilder,
	maxNameChars As Integer,
	colorBuffer As StringBuilder,
	maxColorChars As Integer,
	sizeBuffer As StringBuilder,
	maxSizeChars As Integer
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim themeFileName As StringBuilder
Dim maxNameChars As Integer
Dim colorBuffer As StringBuilder
Dim maxColorChars As Integer
Dim sizeBuffer As StringBuilder
Dim maxSizeChars As Integer
Dim returnValue As Integer

returnValue = NativeMethods.GetCurrentThemeName(themeFileName, 
	maxNameChars, colorBuffer, maxColorChars, 
	sizeBuffer, maxSizeChars)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"UxTheme.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)]
static int GetCurrentThemeName(
	StringBuilder^ themeFileName, 
	int maxNameChars, 
	StringBuilder^ colorBuffer, 
	int maxColorChars, 
	StringBuilder^ sizeBuffer, 
	int maxSizeChars
)
```

**F#**<br />
``` F#
[<DllImportAttribute("UxTheme.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)>]
static member GetCurrentThemeName : 
        themeFileName : StringBuilder * 
        maxNameChars : int * 
        colorBuffer : StringBuilder * 
        maxColorChars : int * 
        sizeBuffer : StringBuilder * 
        maxSizeChars : int -> int 

```


#### Parameters
&nbsp;<dl><dt>themeFileName</dt><dd>Type: System.Text.StringBuilder<br />Pointer to a string that receives the theme path and file name.</dd><dt>maxNameChars</dt><dd>Type: System.Int32<br />The maximum number of characters allowed in the theme file name.</dd><dt>colorBuffer</dt><dd>Type: System.Text.StringBuilder<br />Pointer to a string that receives the color scheme name. 

 This parameter may be set to a null reference (`Nothing` in Visual Basic).</dd><dt>maxColorChars</dt><dd>Type: System.Int32<br />The maximum number of characters allowed in the color scheme name.</dd><dt>sizeBuffer</dt><dd>Type: System.Text.StringBuilder<br />Pointer to a string that receives the size name. 

 This parameter may be set to a null reference (`Nothing` in Visual Basic).</dd><dt>maxSizeChars</dt><dd>Type: System.Int32<br />The maximum number of characters allowed in the size name.</dd></dl>

#### Return Value
Type: Int32<br />Returns `0` if successful, otherwise, an error code.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/bb773365%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/bb773365%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />