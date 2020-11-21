# Converter.ConvertToMP3 Method (String, String, LameBitrate, LameBitrateMode, LameFrequency, LameProfile, LameQuality, LameChannelMode, CoreConverterDspEffect, Boolean, CoreConverterPriority, Int32)
 

Converts a file to MP3 using LAME codec.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_DBpoweramp">DevCase.ThirdParty.DBpoweramp</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public int ConvertToMP3(
	string inFile,
	string outFile,
	LameBitrate bitrate,
	LameBitrateMode bitrateMode,
	LameFrequency frequency,
	LameProfile encodingProfile,
	LameQuality quality,
	LameChannelMode channels,
	CoreConverterDspEffect dspEffects = CoreConverterDspEffect.None,
	bool preserveTags = true,
	CoreConverterPriority priority = CoreConverterPriority.Normal,
	int processorAffinity = 1
)
```

**VB**<br />
``` VB
Public Function ConvertToMP3 ( 
	inFile As String,
	outFile As String,
	bitrate As LameBitrate,
	bitrateMode As LameBitrateMode,
	frequency As LameFrequency,
	encodingProfile As LameProfile,
	quality As LameQuality,
	channels As LameChannelMode,
	Optional dspEffects As CoreConverterDspEffect = CoreConverterDspEffect.None,
	Optional preserveTags As Boolean = true,
	Optional priority As CoreConverterPriority = CoreConverterPriority.Normal,
	Optional processorAffinity As Integer = 1
) As Integer
```

**VB Usage**<br />
``` VB Usage
Dim instance As Converter
Dim inFile As String
Dim outFile As String
Dim bitrate As LameBitrate
Dim bitrateMode As LameBitrateMode
Dim frequency As LameFrequency
Dim encodingProfile As LameProfile
Dim quality As LameQuality
Dim channels As LameChannelMode
Dim dspEffects As CoreConverterDspEffect
Dim preserveTags As Boolean
Dim priority As CoreConverterPriority
Dim processorAffinity As Integer
Dim returnValue As Integer

returnValue = instance.ConvertToMP3(inFile, 
	outFile, bitrate, bitrateMode, frequency, 
	encodingProfile, quality, channels, 
	dspEffects, preserveTags, priority, 
	processorAffinity)
```

**C++**<br />
``` C++
public:
int ConvertToMP3(
	String^ inFile, 
	String^ outFile, 
	LameBitrate bitrate, 
	LameBitrateMode bitrateMode, 
	LameFrequency frequency, 
	LameProfile encodingProfile, 
	LameQuality quality, 
	LameChannelMode channels, 
	CoreConverterDspEffect dspEffects = CoreConverterDspEffect::None, 
	bool preserveTags = true, 
	CoreConverterPriority priority = CoreConverterPriority::Normal, 
	int processorAffinity = 1
)
```

**F#**<br />
``` F#
member ConvertToMP3 : 
        inFile : string * 
        outFile : string * 
        bitrate : LameBitrate * 
        bitrateMode : LameBitrateMode * 
        frequency : LameFrequency * 
        encodingProfile : LameProfile * 
        quality : LameQuality * 
        channels : LameChannelMode * 
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
&nbsp;<dl><dt>inFile</dt><dd>Type: System.String<br />The file to convert.</dd><dt>outFile</dt><dd>Type: System.String<br />The output filepath.</dd><dt>bitrate</dt><dd>Type: <a href="T_DevCase_Core_Multimedia_LameBitrate">DevCase.Core.Multimedia.LameBitrate</a><br />The bitrate.</dd><dt>bitrateMode</dt><dd>Type: <a href="T_DevCase_Core_Multimedia_LameBitrateMode">DevCase.Core.Multimedia.LameBitrateMode</a><br />The bitrate mode.</dd><dt>frequency</dt><dd>Type: <a href="T_DevCase_Core_Multimedia_LameFrequency">DevCase.Core.Multimedia.LameFrequency</a><br />The frequency.</dd><dt>encodingProfile</dt><dd>Type: <a href="T_DevCase_Core_Multimedia_LameProfile">DevCase.Core.Multimedia.LameProfile</a><br />The encoding profile.</dd><dt>quality</dt><dd>Type: <a href="T_DevCase_Core_Multimedia_LameQuality">DevCase.Core.Multimedia.LameQuality</a><br />The encoding quality.</dd><dt>channels</dt><dd>Type: <a href="T_DevCase_Core_Multimedia_LameChannelMode">DevCase.Core.Multimedia.LameChannelMode</a><br />The channel mode.</dd><dt>dspEffects (Optional)</dt><dd>Type: <a href="T_DevCase_ThirdParty_DBpoweramp_CoreConverterDspEffect">DevCase.ThirdParty.DBpoweramp.CoreConverterDspEffect</a><br />The CoreConverter DSP effects.</dd><dt>preserveTags (Optional)</dt><dd>Type: System.Boolean<br />Indicates whether the file should preserve tags after conversion.</dd><dt>priority (Optional)</dt><dd>Type: <a href="T_DevCase_ThirdParty_DBpoweramp_CoreConverterPriority">DevCase.ThirdParty.DBpoweramp.CoreConverterPriority</a><br />The CoreConverter.exe process priority.</dd><dt>processorAffinity (Optional)</dt><dd>Type: System.Int32<br />The amount of processors used by CoreConverter.exe.</dd></dl>

#### Return Value
Type: Int32<br />The process exit code.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_DBpoweramp_Converter">Converter Class</a><br /><a href="Overload_DevCase_ThirdParty_DBpoweramp_Converter_ConvertToMP3">ConvertToMP3 Overload</a><br /><a href="N_DevCase_ThirdParty_DBpoweramp">DevCase.ThirdParty.DBpoweramp Namespace</a><br />