# NativeMethods.GetObject Method 
 

Retrieves information for the specified graphics object.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("GDI32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
public static int GetObject(
	IntPtr hGdiObj,
	int bufferSize,
	IntPtr obj
)
```

**VB**<br />
``` VB
<DllImportAttribute("GDI32.dll", CharSet := CharSet.Auto, BestFitMapping := false, 
	ThrowOnUnmappableChar := true, SetLastError := true>]
Public Shared Function GetObject ( 
	hGdiObj As IntPtr,
	bufferSize As Integer,
	obj As IntPtr
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim hGdiObj As IntPtr
Dim bufferSize As Integer
Dim obj As IntPtr
Dim returnValue As Integer

returnValue = NativeMethods.GetObject(hGdiObj, 
	bufferSize, obj)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"GDI32.dll", CharSet = CharSet::Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)]
static int GetObject(
	IntPtr hGdiObj, 
	int bufferSize, 
	IntPtr obj
)
```

**F#**<br />
``` F#
[<DllImportAttribute("GDI32.dll", CharSet = CharSet.Auto, BestFitMapping = false, 
	ThrowOnUnmappableChar = true, SetLastError = true)>]
static member GetObject : 
        hGdiObj : IntPtr * 
        bufferSize : int * 
        obj : IntPtr -> int 

```


#### Parameters
&nbsp;<dl><dt>hGdiObj</dt><dd>Type: System.IntPtr<br />A handle to the graphics object of interest. 

 This can be a handle to one of the following: a logical bitmap, a brush, a font, a palette, a pen, or a device independent bitmap created by calling the CreateDIBSection function.</dd><dt>bufferSize</dt><dd>Type: System.Int32<br />The number of bytes of information to be written to the buffer.</dd><dt>obj</dt><dd>Type: System.IntPtr<br />A pointer to a buffer that receives the information about the specified graphics object. 

 If the *obj* parameter is NULL, the function return value is the number of bytes required to store the information it writes to the buffer for the specified graphics object.</dd></dl>

#### Return Value
Type: Int32<br />If the function succeeds, and *obj* is a valid pointer, the return value is the number of bytes stored into the buffer. 

 If the function succeeds, and *obj* is NULL, the return value is the number of bytes required to hold the information the function would store into the buffer. 

 If the function fails, the return value is zero.

## Remarks
<a href="https://docs.microsoft.com/en-us/windows/desktop/api/wingdi/nf-wingdi-getobject" target="_blank">https://docs.microsoft.com/en-us/windows/desktop/api/wingdi/nf-wingdi-getobject</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />