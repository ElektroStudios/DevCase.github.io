# CryptoUtil Class
 

Contains cryptography related utilities.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Cryptography.Tools.CryptoUtil<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Cryptography_Tools">DevCase.Core.Cryptography.Tools</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class CryptoUtil : AestheticObject
```

**VB**<br />
``` VB
Public NotInheritable Class CryptoUtil
	Inherits AestheticObject
```

**VB Usage**<br />
``` VB Usage
Dim instance As CryptoUtil
```

**C++**<br />
``` C++
public ref class CryptoUtil sealed : public AestheticObject
```

**F#**<br />
``` F#
[<SealedAttribute>]
type CryptoUtil =  
    class
        inherit AestheticObject
    end
```

The CryptoUtil type exposes the following members.


## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Cryptography_Tools_CryptoUtil_AesDecrypt">AesDecrypt</a></td><td>
Decrypts a string using AES algorithm.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Cryptography_Tools_CryptoUtil_AesEncrypt">AesEncrypt</a></td><td>
Encrypts a string using AES algorithm.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Cryptography_Tools_CryptoUtil_AtbashDecrypt">AtbashDecrypt</a></td><td>
Decrypts a string using Atbash substitution cipher.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Cryptography_Tools_CryptoUtil_AtbashEncrypt">AtbashEncrypt</a></td><td>
Encrypts a string using Atbash substitution cipher.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Cryptography_Tools_CryptoUtil_Base36Decode">Base36Decode</a></td><td>
Decodes a string using Base36 codification.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Cryptography_Tools_CryptoUtil_Base36Encode">Base36Encode</a></td><td>
Encodes a number using Base36 codification.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Cryptography_Tools_CryptoUtil_Base64Decode">Base64Decode</a></td><td>
Decodes a string using Base64 codification.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Cryptography_Tools_CryptoUtil_Base64DecodeAsBitmap">Base64DecodeAsBitmap</a></td><td>
Decodes a string encoded in Base64 to a Bitmap.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")</td><td><a href="M_DevCase_Core_Cryptography_Tools_CryptoUtil_Base64DecodeAsImage">Base64DecodeAsImage</a></td><td>
Decodes a string encoded in Base64 to a Image.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Cryptography_Tools_CryptoUtil_Base64Encode">Base64Encode</a></td><td>
Encodes a string using Base64 codification.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Cryptography_Tools_CryptoUtil_BinaryDecode">BinaryDecode</a></td><td>
Decodes a string using Binary codification.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Cryptography_Tools_CryptoUtil_BinaryEncode">BinaryEncode</a></td><td>
Encodes a string using Binary codification.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Cryptography_Tools_CryptoUtil_CaesarDecrypt">CaesarDecrypt</a></td><td>
Decrypts a string using Caesar's substitution cipher.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Cryptography_Tools_CryptoUtil_CaesarEncrypt">CaesarEncrypt</a></td><td>
Encrypts a string using Caesar's substitution cipher.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Cryptography_Tools_CryptoUtil_ComputeCRC32OfBytes">ComputeCRC32OfBytes</a></td><td>
Computes a CRC-32 checksum for the specified byte array.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Cryptography_Tools_CryptoUtil_ComputeCRC32OfFile">ComputeCRC32OfFile(FileInfo)</a></td><td>
Computes a CRC-32 checksum for the specified file.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Cryptography_Tools_CryptoUtil_ComputeCRC32OfFile_1">ComputeCRC32OfFile(String)</a></td><td>
Computes a CRC-32 checksum for the specified file.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Cryptography_Tools_CryptoUtil_ComputeCRC32OfString">ComputeCRC32OfString(String)</a></td><td>
Computes a CRC-32 checksum for the specified ASCII string.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Cryptography_Tools_CryptoUtil_ComputeCRC32OfString_1">ComputeCRC32OfString(String, Encoding)</a></td><td>
Computes a CRC-32 checksum for the specified string using the specified character encoding.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Cryptography_Tools_CryptoUtil_ComputeCRC64OfBytes">ComputeCRC64OfBytes</a></td><td>
Computes a CRC-64 checksum for the specified byte array.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Cryptography_Tools_CryptoUtil_ComputeCRC64OfFile">ComputeCRC64OfFile(FileInfo)</a></td><td>
Computes a CRC-64 checksum for the specified file.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Cryptography_Tools_CryptoUtil_ComputeCRC64OfFile_1">ComputeCRC64OfFile(String)</a></td><td>
Computes a CRC-64 checksum for the specified file.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Cryptography_Tools_CryptoUtil_ComputeCRC64OfString">ComputeCRC64OfString(String)</a></td><td>
Computes a CRC-64 checksum for the specified ASCII string.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Cryptography_Tools_CryptoUtil_ComputeCRC64OfString_1">ComputeCRC64OfString(String, Encoding)</a></td><td>
Computes a CRC-64 checksum for the specified string using the specified character encoding.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Cryptography_Tools_CryptoUtil_ComputeHashOfBytes__1">ComputeHashOfBytes(T)</a></td><td>
Computes a hash for the specified byte array using the given hash algorithm.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Cryptography_Tools_CryptoUtil_ComputeHashOfFile__1">ComputeHashOfFile(T)(FileInfo)</a></td><td>
Computes a hash for the specified file using the given hash algorithm.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Cryptography_Tools_CryptoUtil_ComputeHashOfFile__1_1">ComputeHashOfFile(T)(String)</a></td><td>
Computes a hash for the specified file using the given hash algorithm.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Cryptography_Tools_CryptoUtil_ComputeHashOfString__1">ComputeHashOfString(T)(String)</a></td><td>
Computes a hash for the specified ASCII string using the given hash algorithm.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Cryptography_Tools_CryptoUtil_ComputeHashOfString__1_1">ComputeHashOfString(T)(String, Encoding)</a></td><td>
Computes a hash for the specified string using the given hash algorithm.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Cryptography_Tools_CryptoUtil_Decrypt__1">Decrypt(T)</a></td><td>
Decrypts a string using the specified SymmetricAlgorithm.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Cryptography_Tools_CryptoUtil_DecryptFile">DecryptFile(SymmetricAlgorithm, FileInfo, FileInfo, String)</a></td><td>
Decrypts a file using the specified SymmetricAlgorithm and writes the decrypted data to a destination file.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Cryptography_Tools_CryptoUtil_DecryptFile_1">DecryptFile(SymmetricAlgorithm, String, String, String)</a></td><td>
Decrypts a file using the specified SymmetricAlgorithm and writes the decrypted data to a destination file.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Cryptography_Tools_CryptoUtil_DecryptFile__1">DecryptFile(T)(FileInfo, FileInfo, String)</a></td><td>
Decrypts a file using the specified SymmetricAlgorithm and writes the decrypted data to a destination file.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Cryptography_Tools_CryptoUtil_DecryptFile__1_1">DecryptFile(T)(String, String, String)</a></td><td>
Decrypts a file using the specified SymmetricAlgorithm and writes the decrypted data to a destination file.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Cryptography_Tools_CryptoUtil_DecryptFileAsString">DecryptFileAsString(SymmetricAlgorithm, FileInfo, String)</a></td><td>
Decrypts a file using the specified SymmetricAlgorithm and returns the decrypted data as a String. 

 This method do not modify the contents of the file.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Cryptography_Tools_CryptoUtil_DecryptFileAsString_1">DecryptFileAsString(SymmetricAlgorithm, String, String)</a></td><td>
Decrypts a file using the specified SymmetricAlgorithm and returns the decrypted data as a String. 

 This method do not modify the contents of the file.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Cryptography_Tools_CryptoUtil_DecryptFileAsString__1">DecryptFileAsString(T)(FileInfo, String)</a></td><td>
Decrypts a file using the specified SymmetricAlgorithm and returns the decrypted data as a String. 

 This method do not modify the contents of the file.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Cryptography_Tools_CryptoUtil_DecryptFileAsString__1_1">DecryptFileAsString(T)(String, String)</a></td><td>
Decrypts a file using the specified SymmetricAlgorithm and returns the decrypted data as a String. 

 This method do not modify the contents of the file.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Cryptography_Tools_CryptoUtil_Encrypt__1">Encrypt(T)</a></td><td>
Encrypts a string using the specified SymmetricAlgorithm.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Cryptography_Tools_CryptoUtil_EncryptFile_1">EncryptFile(SymmetricAlgorithm, FileInfo, String)</a></td><td>
Encrypts a file using the specified SymmetricAlgorithm and writes the encrypted data to the original file.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Cryptography_Tools_CryptoUtil_EncryptFile_2">EncryptFile(SymmetricAlgorithm, String, String)</a></td><td>
Encrypts a file using the specified SymmetricAlgorithm and writes the encrypted data to the original file.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Cryptography_Tools_CryptoUtil_EncryptFile">EncryptFile(SymmetricAlgorithm, FileInfo, FileInfo, String)</a></td><td>
Encrypts a file using the specified SymmetricAlgorithm and writes the encrypted data to a destination file.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Cryptography_Tools_CryptoUtil_EncryptFile_3">EncryptFile(SymmetricAlgorithm, String, String, String)</a></td><td>
Encrypts a file using the specified SymmetricAlgorithm and writes the encrypted data to a destination file.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Cryptography_Tools_CryptoUtil_EncryptFile__1_1">EncryptFile(T)(FileInfo, String)</a></td><td>
Encrypts a file using the specified SymmetricAlgorithm and writes the encrypted data to the original file.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Cryptography_Tools_CryptoUtil_EncryptFile__1_2">EncryptFile(T)(String, String)</a></td><td>
Encrypts a file using the specified SymmetricAlgorithm and writes the encrypted data to the original file.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Cryptography_Tools_CryptoUtil_EncryptFile__1">EncryptFile(T)(FileInfo, FileInfo, String)</a></td><td>
Encrypts a file using the specified SymmetricAlgorithm and writes the encrypted data to a destination file.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Cryptography_Tools_CryptoUtil_EncryptFile__1_3">EncryptFile(T)(String, String, String)</a></td><td>
Encrypts a file using the specified SymmetricAlgorithm and writes the encrypted data to a destination file.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Cryptography_Tools_CryptoUtil_GetRandomHex">GetRandomHex</a></td><td>
Generates a random hexadecimal string of the specified lenth.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Cryptography_Tools_CryptoUtil_GetRandomHexPassword">GetRandomHexPassword</a></td><td>
Generates a random hexadecimal password of the specified amount of secuences delimited by a separator.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Cryptography_Tools_CryptoUtil_GetRandomNumber">GetRandomNumber</a></td><td>
Generates a random numeric value of the specified lenth.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Cryptography_Tools_CryptoUtil_GetRandomNumericPassword">GetRandomNumericPassword</a></td><td>
Generates a random numeric password of the specified amount of secuences delimited by a separator.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Cryptography_Tools_CryptoUtil_GetRandomPassword">GetRandomPassword</a></td><td>
Generates a random alphanumeric password of the specified amount of secuences delimited by a separator.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Cryptography_Tools_CryptoUtil_GetRandomString">GetRandomString</a></td><td>
Generates a random alphanumeric string of the specified lenth.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Cryptography_Tools_CryptoUtil_HexadecimalConvert">HexadecimalConvert(NetSyntaxStyle, String, String)</a></td><td>
Converts an Hexadecimal value to its corresponding representation in the specified language syntax.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Cryptography_Tools_CryptoUtil_HexadecimalConvert__1">HexadecimalConvert(T)(String, String)</a></td><td>
Converts an Hexadecimal value to its corresponding representation of the specified Type.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Cryptography_Tools_CryptoUtil_HexadecimalDecode">HexadecimalDecode</a></td><td>
Decodes a string using Hexadecimal codification.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Cryptography_Tools_CryptoUtil_HexadecimalEncode">HexadecimalEncode</a></td><td>
Encodes a string using Hexadecimal codification.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Cryptography_Tools_CryptoUtil_IsBase64Encoded">IsBase64Encoded</a></td><td>
Determines whether the source string has been `Base64` encoded.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")![Static member](media/static.gif "Static member")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Cryptography_Tools_CryptoUtil_XorEncryptOrDecrypt">XorEncryptOrDecrypt</a></td><td>
Encrypts or decrypts a string using XOR algorithm.</td></tr></table>&nbsp;
<a href="#cryptoutil-class">Back to Top</a>

## Extension Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_CanConvertTo">CanConvertTo(Type)</a></td><td>Overloaded.  
Determines whether the source object can be converted to the specified target type.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_CanConvertTo__1">CanConvertTo(T)()</a></td><td>Overloaded.  
Determines whether the source object can be converted to the specified target type.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_ConvertTo__1">ConvertTo(T)()</a></td><td>Overloaded.  
Converts an object to the specified target type. 

 If the conversion fails, an exception is thrown.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_ConvertTo__1_1">ConvertTo(T)(T)</a></td><td>Overloaded.  
Converts an object to the specified target type. 

 If the conversion fails, returns the specified default value.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr><tr><td>![Public Extension Method](media/pubextension.gif "Public Extension Method")![Code example](media/CodeExample.png "Code example")</td><td><a href="M_DevCase_Core_Extensions_Object_ObjectExtensions_IsDisposable">IsDisposable</a></td><td>
Determines whether the specified object is disposable.
 (Defined by <a href="T_DevCase_Core_Extensions_Object_ObjectExtensions">ObjectExtensions</a>.)</td></tr></table>&nbsp;
<a href="#cryptoutil-class">Back to Top</a>

## See Also


#### Reference
<a href="N_DevCase_Core_Cryptography_Tools">DevCase.Core.Cryptography.Tools Namespace</a><br />