# NativeMethods.GetUserDefaultGeoName Method 
 

Retrieves the two-letter International Organization for Standardization (ISO) 3166-1 code or numeric United Nations (UN) Series M, Number 49 (M.49) code for the default geographical location of the user.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static int GetUserDefaultGeoName(
	StringBuilder geoName,
	int geoNameCount
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function GetUserDefaultGeoName ( 
	geoName As StringBuilder,
	geoNameCount As Integer
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim geoName As StringBuilder
Dim geoNameCount As Integer
Dim returnValue As Integer

returnValue = NativeMethods.GetUserDefaultGeoName(geoName, 
	geoNameCount)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static int GetUserDefaultGeoName(
	StringBuilder^ geoName, 
	int geoNameCount
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member GetUserDefaultGeoName : 
        geoName : StringBuilder * 
        geoNameCount : int -> int 

```


#### Parameters
&nbsp;<dl><dt>geoName</dt><dd>Type: System.Text.StringBuilder<br />Pointer to a buffer in which this function should write the null-terminated two-letter ISO 3166-1 or numeric UN M.49 code for the default geographic location of the user.</dd><dt>geoNameCount</dt><dd>Type: System.Int32<br />The size of the buffer that the *geoName* parameter specifies. 

 If this value is zero, the function only returns the number of characters that function would copy to the output buffer, but does not write the name of the default geographic location of the user to the buffer.</dd></dl>

#### Return Value
Type: Int32<br />The number of characters the function would copy to the output buffer, if the value of the *geoNameCount* parameter is zero. 

 Otherwise, the number of characters that the function copied to the buffer that the *geoName* parameter specifies. 

 A return value of zero indicates that the function failed.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/winnls/nf-winnls-getuserdefaultgeoname" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/winnls/nf-winnls-getuserdefaultgeoname</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />