# NativeMethods.DeviceIoControl Method (IntPtr, UInt32, IntPtr, Int32, IntPtr, Int32, Int32, IntPtr)
 

Sends a control code directly to a specified device driver, causing the corresponding device to perform the corresponding operation.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, SetLastError = true)]
public static bool DeviceIoControl(
	IntPtr hDevice,
	uint ioControlCode,
	IntPtr inputBuffer,
	int inputBufferSize,
	IntPtr outputBuffer,
	int outputBufferSize,
	ref int refBytesReturned,
	IntPtr overlapped
)
```

**VB**<br />
``` VB
<DllImportAttribute("Kernel32.dll", CharSet := CharSet.Auto, SetLastError := true>]
Public Shared Function DeviceIoControl ( 
	hDevice As IntPtr,
	ioControlCode As UInteger,
	inputBuffer As IntPtr,
	inputBufferSize As Integer,
	outputBuffer As IntPtr,
	outputBufferSize As Integer,
	ByRef refBytesReturned As Integer,
	overlapped As IntPtr
) As Boolean
```

**VB Usage**<br />
``` VB Usage
Dim hDevice As IntPtr
Dim ioControlCode As UInteger
Dim inputBuffer As IntPtr
Dim inputBufferSize As Integer
Dim outputBuffer As IntPtr
Dim outputBufferSize As Integer
Dim refBytesReturned As Integer
Dim overlapped As IntPtr
Dim returnValue As Boolean

returnValue = NativeMethods.DeviceIoControl(hDevice, 
	ioControlCode, inputBuffer, inputBufferSize, 
	outputBuffer, outputBufferSize, 
	refBytesReturned, overlapped)
```

**C++**<br />
``` C++
public:
[DllImportAttribute(L"Kernel32.dll", CharSet = CharSet::Auto, SetLastError = true)]
static bool DeviceIoControl(
	IntPtr hDevice, 
	unsigned int ioControlCode, 
	IntPtr inputBuffer, 
	int inputBufferSize, 
	IntPtr outputBuffer, 
	int outputBufferSize, 
	int% refBytesReturned, 
	IntPtr overlapped
)
```

**F#**<br />
``` F#
[<DllImportAttribute("Kernel32.dll", CharSet = CharSet.Auto, SetLastError = true)>]
static member DeviceIoControl : 
        hDevice : IntPtr * 
        ioControlCode : uint32 * 
        inputBuffer : IntPtr * 
        inputBufferSize : int * 
        outputBuffer : IntPtr * 
        outputBufferSize : int * 
        refBytesReturned : int byref * 
        overlapped : IntPtr -> bool 

```


#### Parameters
&nbsp;<dl><dt>hDevice</dt><dd>Type: System.IntPtr<br />A handle to the device on which the operation is to be performed. 

 The device is typically a volume, directory, file, or stream. 

 To retrieve a device handle, use the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CreateFile">CreateFile(String, FileAccessRights, FileShare, IntPtr, FileMode, CreateFileFlags, IntPtr)</a> function.</dd><dt>ioControlCode</dt><dd>Type: System.UInt32<br />The control code for the operation. 

 This value identifies the specific operation to be performed and the type of device on which to perform it.</dd><dt>inputBuffer</dt><dd>Type: System.IntPtr<br />A pointer to the input buffer that contains the data required to perform the operation. 

 The format of this data depends on the value of the *ioControlCode* parameter. 

 This parameter can be a null reference (`Nothing` in Visual Basic) if *ioControlCode* parameter specifies an operation that does not require input data.</dd><dt>inputBufferSize</dt><dd>Type: System.Int32<br />The size of the input buffer specified in the *inputBuffer* parameter, in bytes.</dd><dt>outputBuffer</dt><dd>Type: System.IntPtr<br />A pointer to the output buffer that is to receive the data returned by the operation. 

 The format of this data depends on the value of the dwIoControlCode parameter. 

 This parameter can be a null reference (`Nothing` in Visual Basic) if *ioControlCode* parameter specifies an operation that does not return data.</dd><dt>outputBufferSize</dt><dd>Type: System.Int32<br />The size of the input buffer specified in the *outputBuffer* parameter, in bytes.</dd><dt>refBytesReturned</dt><dd>Type: System.Int32<br />A pointer to a variable that receives the size of the data stored in the output buffer of *outputBuffer* parameter, in bytes. 

 If the output buffer is too small to receive any data, the call fails, GetLastWin32Error() returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">ERROR_INSUFFICIENT_BUFFER</a>, and *refBytesReturned* is zero. 

 If the output buffer is too small to hold all of the data but can hold some entries, some drivers will return as much data as fits. In this case, the call fails, GetLastWin32Error() returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_Win32ErrorCode">ERROR_MORE_DATA</a>, and *refBytesReturned* indicates the amount of data received. Your application should call <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_DeviceIoControl">DeviceIoControl(IntPtr, DirectoryManagementControlCodes, IntPtr, Int32, IntPtr, Int32, Int32, IntPtr)</a> again with the same operation, specifying a new starting point. 

 If *overlapped* is a null reference (`Nothing` in Visual Basic), *refBytesReturned* cannot be a null reference (`Nothing` in Visual Basic). Even when an operation returns no output data and *outputBuffer* is a null reference (`Nothing` in Visual Basic), <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_DeviceIoControl">DeviceIoControl(IntPtr, DirectoryManagementControlCodes, IntPtr, Int32, IntPtr, Int32, Int32, IntPtr)</a> makes use of *refBytesReturned*. After such an operation, the value of *refBytesReturned* is meaningless. 

 If *overlapped* is not a null reference (`Nothing` in Visual Basic), *refBytesReturned* can be a null reference (`Nothing` in Visual Basic). If this parameter is not a null reference (`Nothing` in Visual Basic) and the operation returns data, *refBytesReturned* is meaningless until the overlapped operation has completed. To retrieve the number of bytes returned, call `GetOverlappedResult` function. 

 If *hDevice* is associated with an I/O completion port, you can retrieve the number of bytes returned by calling `GetQueuedCompletionStatus` function.</dd><dt>overlapped</dt><dd>Type: System.IntPtr<br />A pointer to an `OVERLAPPED` structure. 

 If *hDevice* was opened without specifying <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_CreateFileFlags">Overlapped</a> flag, *overlapped* parameter is ignored. 

 If *hDevice* was opened with the <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_CreateFileFlags">Overlapped</a> flag, the operation is performed as an overlapped (asynchronous) operation. In this case, *overlapped* parameter must point to a valid `OVERLAPPED` structure that contains a handle to an event object. Otherwise, the function fails in unpredictable ways. 

 For overlapped operations, <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_DeviceIoControl">DeviceIoControl(IntPtr, DirectoryManagementControlCodes, IntPtr, Int32, IntPtr, Int32, Int32, IntPtr)</a> returns immediately, and the event object is signaled when the operation has been completed. Otherwise, the function does not return until the operation has been completed or an error occurs.</dd></dl>

#### Return Value
Type: Boolean<br />If the operation completes successfully, the return value is `true` (`True` in Visual Basic). 

 If the operation fails or is pending, the return value is `false` (`False` in Visual Basic). 

 To get extended error information, call GetLastWin32Error().

## Remarks
<a href="https://msdn.microsoft.com/es-es/library/windows/desktop/aa363216(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/es-es/library/windows/desktop/aa363216(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_NativeMethods">NativeMethods Class</a><br /><a href="Overload_DevCase_Interop_Unmanaged_Win32_NativeMethods_DeviceIoControl">DeviceIoControl Overload</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />