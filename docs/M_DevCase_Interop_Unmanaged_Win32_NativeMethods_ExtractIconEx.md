# NativeMethods.ExtractIconEx Method 
 

Creates an array of handles to large or small icons extracted from the specified executable file, DLL, or icon file.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Shell32.dll", CharSet = CharSet.Unicode)]
public static int ExtractIconEx(
	string file,
	int uconIndex,
	IntPtr[] hiconLarge,
	IntPtr[] hiconSmall,
	int iconsCount
)
```

**VB**<br />
``` VB
<DllImportAttribute("Shell32.dll", CharSet := CharSet.Unicode>]
Public Shared Function ExtractIconEx ( 
	file As String,
	uconIndex As Integer,
	hiconLarge As IntPtr(),
	hiconSmall As IntPtr(),
	iconsCount As Integer
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim file As String
Dim uconIndex As Integer
Dim hiconLarge As IntPtr()
Dim hiconSmall As IntPtr()
Dim iconsCount As Integer
Dim returnValue As Integer

returnValue = NativeMethods.ExtractIconEx(file, 
	uconIndex, hiconLarge, hiconSmall, 
	iconsCount)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Shell32.dll", CharSet = CharSet::Unicode)]
static int ExtractIconEx(
	String^ file, 
	int uconIndex, 
	array<IntPtr>^ hiconLarge, 
	array<IntPtr>^ hiconSmall, 
	int iconsCount
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Shell32.dll", CharSet = CharSet.Unicode)>]
static member ExtractIconEx : 
        file : string * 
        uconIndex : int * 
        hiconLarge : IntPtr[] * 
        hiconSmall : IntPtr[] * 
        iconsCount : int -> int 

```


#### Parameters
&nbsp;<dl><dt>file</dt><dd>Type: System.String<br />Pointer to a null-terminated string that specifies the name of an executable file, DLL, or icon file from which icons will be extracted.</dd><dt>uconIndex</dt><dd>Type: System.Int32<br />Specifies the zero-based index of the first icon to extract. 

 For example, if this value is zero, the function extracts the first icon in the specified file. 

 If this value is `–1` and *hiconLarge* and *hiconSmall* are both a null reference (`Nothing` in Visual Basic), the function returns the total number of icons in the specified file. 

 If the file is an executable file or DLL, the return value is the number of `RT_GROUP_ICON` resources. 

 If the file is an .ico file, the return value is 1.</dd><dt>hiconLarge</dt><dd>Type: System.IntPtr[]<br />Pointer to an array of icon handles that receives handles to the large icons extracted from the file. 

 If this parameter is a null reference (`Nothing` in Visual Basic), no large icons are extracted from the file.</dd><dt>hiconSmall</dt><dd>Type: System.IntPtr[]<br />Pointer to an array of icon handles that receives handles to the small icons extracted from the file. 

 If this parameter is a null reference (`Nothing` in Visual Basic), no small icons are extracted from the file.</dd><dt>iconsCount</dt><dd>Type: System.Int32<br />The number of icons to extract from the file.</dd></dl>

#### Return Value
Type: Int32<br />If the nIconIndex parameter is `-1`, the *hiconLarge* parameter is a null reference (`Nothing` in Visual Basic), and the *hiconSmall* parameter is a null reference (`Nothing` in Visual Basic), then the return value is the number of icons contained in the specified file. 

 Otherwise, the return value is the number of icons successfully extracted from the file.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/bb776417%28v=vs.85%29.aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/bb776417%28v=vs.85%29.aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />