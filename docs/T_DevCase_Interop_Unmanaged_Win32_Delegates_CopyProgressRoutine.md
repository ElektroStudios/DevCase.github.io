# Delegates.CopyProgressRoutine Delegate
 

An application-defined callback function used with the <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CopyFileEx">CopyFileEx(String, String, Delegates.CopyProgressRoutine, IntPtr, Boolean, CopyFileFlags)</a>, `MoveFileTransacted`, and `MoveFileWithProgress` functions. 

 It is called when a portion of a copy or move operation is completed. 

 The `LPPROGRESS_ROUTINE` type defines a pointer to this callback function. 

Delegates.CopyProgressRoutine is a placeholder for the application-defined function name.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public delegate CopyFileProgressAction CopyProgressRoutine(
	ulong totalFileSize,
	ulong totalBytesTransferred,
	ulong streamSize,
	ulong streamBytesTransferred,
	int streamNumber,
	CopyFileProgressCallbackReason callbackReason,
	IntPtr hSourceFile,
	IntPtr hDestinationFile,
	IntPtr data
)
```

**VB**<br />
``` VB
Public Delegate Function CopyProgressRoutine ( 
	totalFileSize As ULong,
	totalBytesTransferred As ULong,
	streamSize As ULong,
	streamBytesTransferred As ULong,
	streamNumber As Integer,
	callbackReason As CopyFileProgressCallbackReason,
	hSourceFile As IntPtr,
	hDestinationFile As IntPtr,
	data As IntPtr
) As CopyFileProgressAction
```

**VB Usage**<br />
``` VB Usage
Dim instance As New CopyProgressRoutine(AddressOf HandlerMethod)
```

**C++**<br />
``` C++
public delegate CopyFileProgressAction CopyProgressRoutine(
	unsigned long long totalFileSize, 
	unsigned long long totalBytesTransferred, 
	unsigned long long streamSize, 
	unsigned long long streamBytesTransferred, 
	int streamNumber, 
	CopyFileProgressCallbackReason callbackReason, 
	IntPtr hSourceFile, 
	IntPtr hDestinationFile, 
	IntPtr data
)
```

**F#**<br />
``` F#
type CopyProgressRoutine = 
    delegate of 
        totalFileSize : uint64 * 
        totalBytesTransferred : uint64 * 
        streamSize : uint64 * 
        streamBytesTransferred : uint64 * 
        streamNumber : int * 
        callbackReason : CopyFileProgressCallbackReason * 
        hSourceFile : IntPtr * 
        hDestinationFile : IntPtr * 
        data : IntPtr -> CopyFileProgressAction
```


#### Parameters
&nbsp;<dl><dt>totalFileSize</dt><dd>Type: System.UInt64<br />The total size of the file, in bytes.</dd><dt>totalBytesTransferred</dt><dd>Type: System.UInt64<br />The total number of bytes transferred from the source file to the destination file since the copy operation began.</dd><dt>streamSize</dt><dd>Type: System.UInt64<br />The total size of the current file stream, in bytes.</dd><dt>streamBytesTransferred</dt><dd>Type: System.UInt64<br />The total number of bytes in the current stream that have been transferred from the source file to the destination file since the copy operation began.</dd><dt>streamNumber</dt><dd>Type: System.Int32<br />A handle to the current stream. The first time Delegates.CopyProgressRoutine is called, the stream number is 1.</dd><dt>callbackReason</dt><dd>Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_CopyFileProgressCallbackReason">DevCase.Interop.Unmanaged.Win32.Enums.CopyFileProgressCallbackReason</a><br />The reason that Delegates.CopyProgressRoutine was called.</dd><dt>hSourceFile</dt><dd>Type: System.IntPtr<br />A handle to the source file.</dd><dt>hDestinationFile</dt><dd>Type: System.IntPtr<br />A handle to the destination file.</dd><dt>data</dt><dd>Type: System.IntPtr<br />Argument passed to Delegates.CopyProgressRoutine by <a href="M_DevCase_Interop_Unmanaged_Win32_NativeMethods_CopyFileEx">CopyFileEx(String, String, Delegates.CopyProgressRoutine, IntPtr, Boolean, CopyFileFlags)</a>, `MoveFileTransacted`, or `MoveFileWithProgress` functions.</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_CopyFileProgressAction">CopyFileProgressAction</a><br />The Delegates.CopyProgressRoutine function should return one of the following values: 

<a href="T_DevCase_Interop_Unmanaged_Win32_Enums_CopyFileProgressAction">Cancel</a> - Cancel the copy operation and delete the destination file. 

<a href="T_DevCase_Interop_Unmanaged_Win32_Enums_CopyFileProgressAction">Continue</a> - Continue the copy operation. 

<a href="T_DevCase_Interop_Unmanaged_Win32_Enums_CopyFileProgressAction">Quiet</a> - Continue the copy operation, but stop invoking Delegates.CopyProgressRoutine to report progress. 

<a href="T_DevCase_Interop_Unmanaged_Win32_Enums_CopyFileProgressAction">Stop</a> - Stop the copy operation. It can be restarted at a later time.

## Remarks
<a href="https://msdn.microsoft.com/en-us/library/windows/desktop/aa363854(v=vs.85).aspx" target="_blank">https://msdn.microsoft.com/en-us/library/windows/desktop/aa363854(v=vs.85).aspx</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32">DevCase.Interop.Unmanaged.Win32 Namespace</a><br />