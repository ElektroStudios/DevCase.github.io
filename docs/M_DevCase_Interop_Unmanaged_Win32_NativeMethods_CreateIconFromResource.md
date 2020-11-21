# NativeMethods.CreateIconFromResource Method 
 

Creates an icon or cursor from resource bits describing the icon. 

 To specify a desired height or width, use the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CreateIconFromResourceEx">CreateIconFromResourceEx(Byte, UInt32, Boolean, UInt32, Int32, Int32, CreateIconFromResourceFlags)</a> function

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("User32.dll", SetLastError = true)]
public static IntPtr CreateIconFromResource(
	ref byte refResourceBits,
	uint resourceSize,
	bool isIcon,
	uint version
)
```

**VB**<br />
``` VB
<DllImportAttribute("User32.dll", SetLastError := true>]
Public Shared Function CreateIconFromResource ( 
	ByRef refResourceBits As Byte,
	resourceSize As UInteger,
	isIcon As Boolean,
	version As UInteger
) As IntPtr
```

**VB Usage**<br />
``` VB Usage
Dim refResourceBits As Byte
Dim resourceSize As UInteger
Dim isIcon As Boolean
Dim version As UInteger
Dim returnValue As IntPtr

returnValue = NativeMethods.CreateIconFromResource(refResourceBits, 
	resourceSize, isIcon, version)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"User32.dll", SetLastError = true)]
static IntPtr CreateIconFromResource(
	unsigned char% refResourceBits, 
	unsigned int resourceSize, 
	bool isIcon, 
	unsigned int version
)
```

**F#**<br />
``` F#
[<DllImportAttribute("User32.dll", SetLastError = true)>]
static member CreateIconFromResource : 
        refResourceBits : byte byref * 
        resourceSize : uint32 * 
        isIcon : bool * 
        version : uint32 -> IntPtr 

```


#### Parameters
&nbsp;<dl><dt>refResourceBits</dt><dd>Type: System.Byte<br />The buffer containing the icon or cursor resource bits. 

 These bits are typically loaded by calls to the LookupIconIdFromDirectory, LookupIconIdFromDirectoryEx, and <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_LoadResource">LoadResource(SafeModuleHandle, IntPtr)</a> functions.</dd><dt>resourceSize</dt><dd>Type: System.UInt32<br />The size, in bytes, of the set of bits pointed to by the *refResourceBits* parameter.</dd><dt>isIcon</dt><dd>Type: System.Boolean<br />Indicates whether an icon or a cursor is to be created. 

 If this parameter is `true` (`True` in Visual Basic), an icon is to be created. If it is `false` (`False` in Visual Basic), a cursor is to be created.</dd><dt>version</dt><dd>Type: System.UInt32<br />The version number of the icon or cursor format for the resource bits pointed to by the presbits parameter. The value must be greater than or equal to `0x00020000` (`&H20000` in VB.NET) and less than or equal to `0x00030000` (`&H30000` in VB.NET). This parameter is generally set to `0x00030000` (`&H30000` in VB.NET).</dd></dl>

#### Return Value
Type: IntPtr<br />If the function succeeds, the return value is a handle to the icon or cursor. 

 If the function fails, the return value is Zero. 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/ms648060(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/ms648060(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />