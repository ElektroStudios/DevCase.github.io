# NativeMethods.FillMemory Method 
 

Fills a block of memory with a specified value.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", EntryPoint = "RtlFillMemory", SetLastError = true)]
public static void FillMemory(
	IntPtr destination,
	IntPtr length,
	byte fillValue
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", EntryPoint := "RtlFillMemory", SetLastError := true>]
Public Shared Sub FillMemory ( 
	destination As IntPtr,
	length As IntPtr,
	fillValue As Byte
)
```

**VB Usage**<br />
``` VB Usage
Dim destination As IntPtr
Dim length As IntPtr
Dim fillValue As ByteNativeMethods.FillMemory(destination, length, 
	fillValue)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", EntryPoint = L"RtlFillMemory", SetLastError = true)]
static void FillMemory(
	IntPtr destination, 
	IntPtr length, 
	unsigned char fillValue
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", EntryPoint = "RtlFillMemory", SetLastError = true)>]
static member FillMemory : 
        destination : IntPtr * 
        length : IntPtr * 
        fillValue : byte -> unit 

```


#### Parameters
&nbsp;<dl><dt>destination</dt><dd>Type: System.IntPtr<br />A pointer to the starting address of the block of memory to fill.</dd><dt>length</dt><dd>Type: System.IntPtr<br />The size of the block of memory to fill, in bytes. This value must be less than the size of the *destination* buffer.</dd><dt>fillValue</dt><dd>Type: System.Byte<br />The byte value with which to fill the memory block.</dd></dl>

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/aa366561(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/aa366561(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />