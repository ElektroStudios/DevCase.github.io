# SnesRom Class
 

Represents a SNES ROM.


## Inheritance Hierarchy
System.Object<br />&nbsp;&nbsp;<a href="T_DevCase_Core_Design_AestheticObject">DevCase.Core.Design.AestheticObject</a><br />&nbsp;&nbsp;&nbsp;&nbsp;DevCase.Core.Multimedia.Gaming.SnesRom<br />
**Namespace:**&nbsp;<a href="N_DevCase_Core_Multimedia_Gaming">DevCase.Core.Multimedia.Gaming</a><br />**Assembly:**&nbsp;DevCase.Core (in DevCase.Core.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public sealed class SnesRom : AestheticObject
```

**VB**<br />
``` VB
Public NotInheritable Class SnesRom
	Inherits AestheticObject
```

**VB Usage**<br />
``` VB Usage
Dim instance As SnesRom
```

**C++**<br />
``` C++
public ref class SnesRom sealed : public AestheticObject
```

**F#**<br />
``` F#
[<SealedAttribute>]
type SnesRom =  
    class
        inherit AestheticObject
    end
```

The SnesRom type exposes the following members.


## Constructors
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Multimedia_Gaming_SnesRom__ctor">SnesRom(Byte[])</a></td><td>
Initializes a new instance of the SnesRom class.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Multimedia_Gaming_SnesRom__ctor_1">SnesRom(FileInfo)</a></td><td>
Initializes a new instance of the SnesRom class.</td></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Multimedia_Gaming_SnesRom__ctor_2">SnesRom(String)</a></td><td>
Initializes a new instance of the SnesRom class.</td></tr></table>&nbsp;
<a href="#snesrom-class">Back to Top</a>

## Properties
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Multimedia_Gaming_SnesRom_BankType">BankType</a></td><td>
Gets the bank type. 

 An image contains only LoROM banks or only HiROM banks, not both.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Multimedia_Gaming_SnesRom_CartridgeType">CartridgeType</a></td><td>
Gets the cartrifge type, it can be a ROM only, or a ROM with save-RAM.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Multimedia_Gaming_SnesRom_Checksum">Checksum</a></td><td>
Gets the checksum.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Multimedia_Gaming_SnesRom_ChecksumComplement">ChecksumComplement</a></td><td>
Gets the checksum complement.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Multimedia_Gaming_SnesRom_Country">Country</a></td><td>
Gets or sets the country data.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Multimedia_Gaming_SnesRom_HeaderType">HeaderType</a></td><td>
Gets The ROM header type.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Multimedia_Gaming_SnesRom_Layout">Layout</a></td><td>
Gets the ROM layout. 

 The SNES ROM layout describes how the ROM banks appear in a ROM image and in the SNES address space.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Multimedia_Gaming_SnesRom_LicenseCode">LicenseCode</a></td><td>
Gets or sets the license code.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Multimedia_Gaming_SnesRom_Name">Name</a></td><td>
Gets or sets the name of the ROM, typically in ASCII. 

 The name buffer consists in 21 characters.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Multimedia_Gaming_SnesRom_RamSize">RamSize</a></td><td>
Gets or sets the RAM size, in kilobits. 

 If the return value is 0, the ROM has no RAM.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Multimedia_Gaming_SnesRom_RawData">RawData</a></td><td>
Gets the raw byte-data of the ROM file.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Multimedia_Gaming_SnesRom_RomSize">RomSize</a></td><td>
Gets or sets the ROM size, in megabits.</td></tr><tr><td>![Public property](media/pubproperty.gif "Public property")</td><td><a href="P_DevCase_Core_Multimedia_Gaming_SnesRom_Version">Version</a></td><td>
Gets or sets the version number.</td></tr></table>&nbsp;
<a href="#snesrom-class">Back to Top</a>

## Methods
&nbsp;<table><tr><th></th><th>Name</th><th>Description</th></tr><tr><td>![Public method](media/pubmethod.gif "Public method")</td><td><a href="M_DevCase_Core_Multimedia_Gaming_SnesRom_Save">Save</a></td><td>
Save the ROM changes to the specified file path.</td></tr></table>&nbsp;
<a href="#snesrom-class">Back to Top</a>

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
<a href="#snesrom-class">Back to Top</a>

## Remarks
Original implementation: <a href="http://github.com/Zeokat/SNES-ROM-Header-Dumper-CSharp/blob/master/snes_dumper.cs" target="_blank">http://github.com/Zeokat/SNES-ROM-Header-Dumper-CSharp/blob/master/snes_dumper.cs</a>

## Examples
This is a code example that illustrates how to read a SNES ROM. 
**VB**<br />
``` VB
Dim rom As New SnesRom("C:\ROM.smc")

Dim sb As New Global.System.Text.StringBuilder()
With sb
    .AppendLine(String.Format("Name..................: {0}", rom.Name))
    .AppendLine(String.Format("Bank Type.............: {0}", rom.BankType.ToString()))
    .AppendLine(String.Format("Cartridge Type........: {0}", rom.CartridgeType.ToString().ToUpper().Replace("_", "/")))
    .AppendLine(String.Format("Checksum..............: {0}", String.Format("0x{0}", Convert.ToString(CInt(rom.Checksum), toBase:=16).ToUpper())))
    .AppendLine(String.Format("Checksum Complement...: {0}", String.Format("0x{0}", Convert.ToString(CInt(rom.ChecksumComplement), toBase:=16).ToUpper())))
    .AppendLine(String.Format("Country Code..........: {0}", rom.Country.Code.ToString()))
    .AppendLine(String.Format("Country Name..........: {0}", rom.Country.Name))
    .AppendLine(String.Format("Country Region........: {0}", rom.Country.Region.ToString().ToUpper()))
    .AppendLine(String.Format("Header Type (SMC).....: {0}", rom.HeaderType.ToString()))
    .AppendLine(String.Format("Layout................: {0}", rom.Layout.ToString()))
    .AppendLine(String.Format("License Code/Name.....: {0}", rom.LicenseCode.ToString()))
    .AppendLine(String.Format("ROM Size..............: {0} MBits", rom.RomSize.ToString().Replace("Mbits", "").Replace("or", "/")))
    .AppendLine(String.Format("RAM Size..............: {0} KBits", rom.RamSize.ToString().Replace("Kbits", "")))
    .AppendLine(String.Format("Version Number........: 1.{0}", rom.Version.ToString()))
End With

Clipboard.SetText(sb.ToString())
Console.WriteLine(sb.ToString())
```


## Examples
This is a code example that illustrates how to modify a SNES ROM. 
**VB**<br />
``` VB
Dim rom As New SnesRom("C:\ROM.smc")

With rom
    .Name = "Elektro"
    .Version = 1
    .Country = New SnesRomCountry(countryCode:=0) ' Japan.
    .LicenseCode = SnesLicenseCodeEnum.Taito
    .RomSize = SnesRomSizeEnum.Mbits4
    .RamSize = SnesSramSizeEnum.Kbits256
    .Save("C:\New.smc", replace:=True)
End With
```


## See Also


#### Reference
<a href="N_DevCase_Core_Multimedia_Gaming">DevCase.Core.Multimedia.Gaming Namespace</a><br />