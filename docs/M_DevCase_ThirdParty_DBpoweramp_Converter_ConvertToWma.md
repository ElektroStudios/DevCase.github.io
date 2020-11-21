# Converter.ConvertToWma Method (FileInfo, String, Wma9Bitrate, Wma9Frequency, Wma9ChannelMode, CoreConverterDspEffect, Boolean, CoreConverterPriority, Int32)
 

Converts a file to WMA v9.2

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_DBpoweramp">DevCase.ThirdParty.DBpoweramp</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public int ConvertToWma(
	FileInfo inFile,
	string outFile,
	Wma9Bitrate bitrate,
	Wma9Frequency frequency,
	Wma9ChannelMode channels,
	CoreConverterDspEffect dspEffects = CoreConverterDspEffect.None,
	bool preserveTags = true,
	CoreConverterPriority priority = CoreConverterPriority.Normal,
	int processorAffinity = 1
)
```

**VB**<br />
``` VB
Public Function ConvertToWma ( 
	inFile As FileInfo,
	outFile As String,
	bitrate As Wma9Bitrate,
	frequency As Wma9Frequency,
	channels As Wma9ChannelMode,
	Optional dspEffects As CoreConverterDspEffect = CoreConverterDspEffect.None,
	Optional preserveTags As Boolean = true,
	Optional priority As CoreConverterPriority = CoreConverterPriority.Normal,
	Optional processorAffinity As Integer = 1
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim instance As Converter
Dim inFile As FileInfo
Dim outFile As String
Dim bitrate As Wma9Bitrate
Dim frequency As Wma9Frequency
Dim channels As Wma9ChannelMode
Dim dspEffects As CoreConverterDspEffect
Dim preserveTags As Boolean
Dim priority As CoreConverterPriority
Dim processorAffinity As Integer
Dim returnValue As Integer

returnValue = instance.ConvertToWma(inFile, 
	outFile, bitrate, frequency, channels, 
	dspEffects, preserveTags, priority, 
	processorAffinity)
```

**C++**<br />
``` C++
public:
int ConvertToWma(
	FileInfo^ inFile, 
	String^ outFile, 
	Wma9Bitrate bitrate, 
	Wma9Frequency frequency, 
	Wma9ChannelMode channels, 
	CoreConverterDspEffect dspEffects = CoreConverterDspEffect::None, 
	bool preserveTags = true, 
	CoreConverterPriority priority = CoreConverterPriority::Normal, 
	int processorAffinity = 1
)
```

**F#**<br />
``` F#
member ConvertToWma : 
        inFile : FileInfo * 
        outFile : string * 
        bitrate : Wma9Bitrate * 
        frequency : Wma9Frequency * 
        channels : Wma9ChannelMode * 
        ?dspEffects : CoreConverterDspEffect * 
        ?preserveTags : bool * 
        ?priority : CoreConverterPriority * 
        ?processorAffinity : int 
(* Defaults:
        let _dspEffects = defaultArg dspEffects CoreConverterDspEffect.None
        let _preserveTags = defaultArg preserveTags true
        let _priority = defaultArg priority CoreConverterPriority.Normal
        let _processorAffinity = defaultArg processorAffinity 1
*)
-> int 

```


#### Parameters
&nbsp;<dl><dt>inFile</dt><dd>Type: System.IO.FileInfo<br />The file to convert.</dd><dt>outFile</dt><dd>Type: System.String<br />The output filepath.</dd><dt>bitrate</dt><dd>Type: <a href="T_DevCase_Core_Multimedia_Wma9Bitrate">DevCase.Core.Multimedia.Wma9Bitrate</a><br />The bitrate.</dd><dt>frequency</dt><dd>Type: <a href="T_DevCase_Core_Multimedia_Wma9Frequency">DevCase.Core.Multimedia.Wma9Frequency</a><br />The frequency.</dd><dt>channels</dt><dd>Type: <a href="T_DevCase_Core_Multimedia_Wma9ChannelMode">DevCase.Core.Multimedia.Wma9ChannelMode</a><br />The channel mode.</dd><dt>dspEffects (Optional)</dt><dd>Type: <a href="T_DevCase_ThirdParty_DBpoweramp_CoreConverterDspEffect">DevCase.ThirdParty.DBpoweramp.CoreConverterDspEffect</a><br />The CoreConverter DSP effects.</dd><dt>preserveTags (Optional)</dt><dd>Type: System.Boolean<br />Indicates whether the file should preserve tags after conversion.</dd><dt>priority (Optional)</dt><dd>Type: <a href="T_DevCase_ThirdParty_DBpoweramp_CoreConverterPriority">DevCase.ThirdParty.DBpoweramp.CoreConverterPriority</a><br />The CoreConverter.exe process priority.</dd><dt>processorAffinity (Optional)</dt><dd>Type: System.Int32<br />The amount of processors used by CoreConverter.exe.</dd></dl>

#### Return Value
Type: Int32<br />The process exit code.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_DBpoweramp_Converter">Converter Class</a><br /><a href="Overload_DevCase_ThirdParty_DBpoweramp_Converter_ConvertToWma">ConvertToWma Overload</a><br /><a href="N_DevCase_ThirdParty_DBpoweramp">DevCase.ThirdParty.DBpoweramp Namespace</a><br />