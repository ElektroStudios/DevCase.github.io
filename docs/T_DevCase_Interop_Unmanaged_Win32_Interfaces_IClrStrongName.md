# IClrStrongName Interface
 

Provides basic global static functions for signing assemblies with strong names.

**Namespace:**&nbsp;<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces</a><br />**Assembly:**&nbsp;DevCase.Interop (in DevCase.Interop.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[ComImportAttribute]
[GuidAttribute("9FD93CCF-3280-4391-B3A9-96E1CDE77C8D")]
[InterfaceTypeAttribute(ComInterfaceType.InterfaceIsIUnknown)]
[SecurityCriticalAttribute]
public interface IClrStrongName
```

**VB**<br />
``` VB
<ComImportAttribute>
<GuidAttribute("9FD93CCF-3280-4391-B3A9-96E1CDE77C8D")>
<InterfaceTypeAttribute(ComInterfaceType.InterfaceIsIUnknown)>
<SecurityCriticalAttribute>
Public Interface IClrStrongName
```

**VB Usage**<br />
``` VB Usage
Dim instance As IClrStrongName
```

**C++**<br />
``` C++
[ComImportAttribute]
[GuidAttribute(L"9FD93CCF-3280-4391-B3A9-96E1CDE77C8D")]
[InterfaceTypeAttribute(ComInterfaceType::InterfaceIsIUnknown)]
[SecurityCriticalAttribute]
public interface class IClrStrongName
```

**F#**<br />
``` F#
[<ComImportAttribute>]
[<GuidAttribute("9FD93CCF-3280-4391-B3A9-96E1CDE77C8D")>]
[<InterfaceTypeAttribute(ComInterfaceType.InterfaceIsIUnknown)>]
[<SecurityCriticalAttribute>]
type IClrStrongName =  interface end
```

The IClrStrongName type exposes the following members.


## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IClrStrongName_GetHashFromAssemblyFile">GetHashFromAssemblyFile</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IClrStrongName_GetHashFromAssemblyFileW">GetHashFromAssemblyFileW</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IClrStrongName_GetHashFromBlob">GetHashFromBlob</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IClrStrongName_GetHashFromFile">GetHashFromFile</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IClrStrongName_GetHashFromFileW">GetHashFromFileW</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IClrStrongName_GetHashFromHandle">GetHashFromHandle</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IClrStrongName_StrongNameCompareAssemblies">StrongNameCompareAssemblies</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IClrStrongName_StrongNameFreeBuffer">StrongNameFreeBuffer</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IClrStrongName_StrongNameGetBlob">StrongNameGetBlob</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IClrStrongName_StrongNameGetBlobFromImage">StrongNameGetBlobFromImage</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IClrStrongName_StrongNameGetPublicKey">StrongNameGetPublicKey</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IClrStrongName_StrongNameHashSize">StrongNameHashSize</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IClrStrongName_StrongNameKeyDelete">StrongNameKeyDelete</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IClrStrongName_StrongNameKeyGen">StrongNameKeyGen</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IClrStrongName_StrongNameKeyGenEx">StrongNameKeyGenEx</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IClrStrongName_StrongNameKeyInstall">StrongNameKeyInstall</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IClrStrongName_StrongNameSignatureGeneration">StrongNameSignatureGeneration</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IClrStrongName_StrongNameSignatureGenerationEx">StrongNameSignatureGenerationEx</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IClrStrongName_StrongNameSignatureSize">StrongNameSignatureSize</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IClrStrongName_StrongNameSignatureVerification">StrongNameSignatureVerification</a></td><td>
Gets a value that indicates whether the assembly manifest at the supplied path contains a strong name signature, which is verified according to the specified flags.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IClrStrongName_StrongNameSignatureVerificationEx">StrongNameSignatureVerificationEx</a></td><td>
Gets a value that indicates whether the assembly manifest at the supplied path contains a strong name signature.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IClrStrongName_StrongNameSignatureVerificationFromImage">StrongNameSignatureVerificationFromImage</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IClrStrongName_StrongNameTokenFromAssembly">StrongNameTokenFromAssembly</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IClrStrongName_StrongNameTokenFromAssemblyEx">StrongNameTokenFromAssemblyEx</a></td><td /></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Interop_Unmanaged_Win32_Interfaces_IClrStrongName_StrongNameTokenFromPublicKey">StrongNameTokenFromPublicKey</a></td><td /></tr></table>&nbsp;
<a href="#iclrstrongname-interface">Back to Top</a>

## Remarks
<a href="https://docs.microsoft.com/en-us/dotnet/framework/unmanaged-api/hosting/iclrstrongname-interface" target="_blank">https://docs.microsoft.com/en-us/dotnet/framework/unmanaged-api/hosting/iclrstrongname-interface</a>

## See Also


#### Reference
<a href="N_DevCase_Interop_Unmanaged_Win32_Interfaces">DevCase.Interop.Unmanaged.Win32.Interfaces Namespace</a><br />