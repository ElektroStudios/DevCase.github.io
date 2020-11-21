# NativeMethods.GetUserDefaultLocaleName Method 
 

Retrieves the user default locale name.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", CharSet = CharSet.Unicode, ExactSpelling = true, 
	SetLastError = true)]
public static bool GetUserDefaultLocaleName(
	StringBuilder localeName,
	int length
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", CharSet := CharSet.Unicode, ExactSpelling := true, 
	SetLastError := true>]
Public Shared Function GetUserDefaultLocaleName ( 
	localeName As StringBuilder,
	length As Integer
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim localeName As StringBuilder
Dim length As Integer
Dim returnValue As Boolean

returnValue = NativeMethods.GetUserDefaultLocaleName(localeName, 
	length)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", CharSet = CharSet::Unicode, ExactSpelling = true, 
	SetLastError = true)]
static bool GetUserDefaultLocaleName(
	StringBuilder^ localeName, 
	int length
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", CharSet = CharSet.Unicode, ExactSpelling = true, 
	SetLastError = true)>]
static member GetUserDefaultLocaleName : 
        localeName : StringBuilder * 
        length : int -> bool 

```


#### Parameters
&nbsp;<dl><dt>localeName</dt><dd>Type: System.Text.StringBuilder<br />Pointer to a buffer in which this function retrieves the locale name.</dd><dt>length</dt><dd>Type: System.Int32<br />Size, in characters, of the buffer indicated by *localeName* parameter. 

 The maximum possible length of a locale name, including a terminating null character, is LOCALE_NAME_MAX_LENGTH. This is the recommended size to supply in this parameter.</dd></dl>

#### Return Value
Type: Boolean<br />If the function succeeds, the return value is the size of the buffer containing the locale name, including the terminating null character. 

 If the function fails, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winnls/nf-winnls-getuserdefaultlocalename" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winnls/nf-winnls-getuserdefaultlocalename</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />