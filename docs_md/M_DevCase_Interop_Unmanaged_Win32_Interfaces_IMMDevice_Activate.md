# IMMDevice.Activate Method 
 

Creates a COM object with the specified interface

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[PreserveSigAttribute]
HResult Activate(
	ref Guid refId,
	int clsCtx,
	IntPtr activationParams,
	ref Object refInterface
)
```

**VB**<br />
``` VB
<PreserveSigAttribute>
Function Activate ( 
	ByRef refId As Guid,
	clsCtx As Integer,
	activationParams As IntPtr,
	ByRef refInterface As Object
) As HResult
```

**VB Usage**<br />
``` VB Usage
Dim instance As IMMDevice
Dim refId As Guid
Dim clsCtx As Integer
Dim activationParams As IntPtr
Dim refInterface As Object
Dim returnValue As HResult

returnValue = instance.Activate(refId, 
	clsCtx, activationParams, refInterface)
```

**C++**<br />
``` C++
[PreserveSigAttribute]
HResult Activate(
	Guid% refId, 
	int clsCtx, 
	IntPtr activationParams, 
	Object^% refInterface
)
```

**F#**<br />
``` F#
[<PreserveSigAttribute>]
abstract Activate : 
        refId : Guid byref * 
        clsCtx : int * 
        activationParams : IntPtr * 
        refInterface : Object byref -> HResult 

```


#### Parameters
&nbsp;<dl><dt>refId</dt><dd>Type: System.Guid<br />The interface identifier. 

 This parameter is a reference to a GUID that identifies the interface that the caller requests be activated. 

 The caller will use this interface to communicate with the COM object.</dd><dt>clsCtx</dt><dd>Type: System.Int32<br />The execution context in which the code that manages the newly created object will run. 

 The caller can restrict the context by setting this parameter to the bitwise OR of one or more CLSCTX enumeration values. 

 Alternatively, the client can avoid imposing any context restrictions by specifying CLSCTX_ALL.</dd><dt>activationParams</dt><dd>Type: System.IntPtr<br />Set to Zero to activate an IAudioClient, IAudioEndpointVolume, IAudioMeterInformation, <a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IAudioSessionManager">IAudioSessionManager</a>, or IDeviceTopology interface on an audio endpoint device. 

 When activating an IBaseFilter, IDirectSound, IDirectSound8, IDirectSoundCapture, or IDirectSoundCapture8 interface on the device, the caller can specify a pointer to a PROPVARIANT structure that contains stream-initialization information.</dd><dt>refInterface</dt><dd>Type: System.Object<br />Pointer to a pointer variable into which the method writes the address of the interface specified by parameter *refId*. 

 Through this method, the caller obtains a counted reference to the interface. 

 The caller is responsible for releasing the interface, when it is no longer needed, by calling the interface's Release method. 

 If the Activate(Guid, Int32, IntPtr, Object) call fails, *refInterface* is a null reference (`Nothing` in Visual Basic).</dd></dl>

#### Return Value
Type: <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a><br />If the method succeeds, it returns <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">S_OK</a>. If it fails, it returns an <a href="T_DevCase_Interop_Unmanaged_Win32_Enums_HResult">HResult</a> value.

## See Also


#### Reference
<a href="T_DevCase_Interop_Unmanaged_Win32_Interfaces_IMMDevice">IMMDevice Interface</a><br /><a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />