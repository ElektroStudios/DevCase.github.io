# NativeMethods.GetMenuString Method (IntPtr, UInt32, StringBuilder, Int32, MenuPosition)
 

Copies the text string of the specified menu item into the specified buffer.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)]
public static int GetMenuString(
	IntPtr hMenu,
	uint uIDItem,
	StringBuilder lpString,
	int nMaxCount,
	MenuPosition uFlags
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true>]
Public Shared Function GetMenuString ( 
	hMenu As IntPtr,
	uIDItem As UInteger,
	<OutAttribute> lpString As StringBuilder,
	nMaxCount As Integer,
	uFlags As MenuPosition
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim hMenu As IntPtr
Dim uIDItem As UInteger
Dim lpString As StringBuilder
Dim nMaxCount As Integer
Dim uFlags As MenuPosition
Dim returnValue As Integer

returnValue = NativeMethods.GetMenuString(hMenu, 
	uIDItem, lpString, nMaxCount, uFlags)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)]
static int GetMenuString(
	IntPtr hMenu, 
	unsigned int uIDItem, 
	[OutAttribute] StringBuilder^ lpString, 
	int nMaxCount, 
	MenuPosition uFlags
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true)>]
static member GetMenuString : 
        hMenu : IntPtr * 
        uIDItem : uint32 * 
        lpString : StringBuilder byref * 
        nMaxCount : int * 
        uFlags : MenuPosition -> int 

```


#### Parameters
&nbsp;<dl><dt>hMenu</dt><dd>Type: System.IntPtr<br />A handle to the menu.</dd><dt>uIDItem</dt><dd>Type: System.UInt32<br />The menu item to be changed, as determined by the *uFlags* parameter.</dd><dt>lpString</dt><dd>Type: System.Text.StringBuilder<br />The buffer that receives the null-terminated string. 

 If the string is as long or longer than *lpString*, the string is truncated and the terminating null character is added. 

 If *lpString* is a null reference (`Nothing` in Visual Basic), the function returns the length of the menu string.</dd><dt>nMaxCount</dt><dd>Type: System.Int32<br />The maximum length, in characters, of the string to be copied. 

 If the string is longer than the maximum specified in the *nMaxCount* parameter, the extra characters are truncated. 

 If nMaxCount is `0`, the function returns the length of the menu string.</dd><dt>uFlags</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_MenuPosition">DevCase.Interop.Unmanaged.Win32.Enums.MenuPosition</a><br />Indicates how the *uIDItem* parameter is interpreted.</dd></dl>

#### Return Value
Type: Int32<br />If the function succeeds, the return value specifies the number of characters copied to the buffer, not including the terminating null character. 

 If the function fails, the return value is zero. 

 If the specified item is not of type `MIIM_STRING` or `MFT_STRING`, then the return value is zero.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms647983%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms647983%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_GetMenuString">GetMenuString Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />