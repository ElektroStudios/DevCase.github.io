# Converter.ConvertToWav Method (FileInfo, String, WavBitdepth, WavFrequency, WavChannelMode, CoreConverterDspEffect, Boolean, CoreConverterPriority, Int32)
 

Converts a file to uncompressed WAV.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_DBpoweramp">DevCase.ThirdParty.DBpoweramp</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public int ConvertToWav(
	FileInfo inFile,
	string outFile,
	WavBitdepth bitDepth,
	WavFrequency frequency,
	WavChannelMode channels,
	CoreConverterDspEffect dspEffects = CoreConverterDspEffect.None,
	bool preserveTags = true,
	CoreConverterPriority priority = CoreConverterPriority.Normal,
	int processorAffinity = 1
)
```

**VB**<br />
``` VB
Public Function ConvertToWav ( 
	inFile As FileInfo,
	outFile As String,
	bitDepth As WavBitdepth,
	frequency As WavFrequency,
	channels As WavChannelMode,
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
Dim bitDepth As WavBitdepth
Dim frequency As WavFrequency
Dim channels As WavChannelMode
Dim dspEffects As CoreConverterDspEffect
Dim preserveTags As Boolean
Dim priority As CoreConverterPriority
Dim processorAffinity As Integer
Dim returnValue As Integer

returnValue = instance.ConvertToWav(inFile, 
	outFile, bitDepth, frequency, channels, 
	dspEffects, preserveTags, priority, 
	processorAffinity)
```

**C++**<br />
``` C++
public:
int ConvertToWav(
	FileInfo^ inFile, 
	String^ outFile, 
	WavBitdepth bitDepth, 
	WavFrequency frequency, 
	WavChannelMode channels, 
	CoreConverterDspEffect dspEffects = CoreConverterDspEffect::None, 
	bool preserveTags = true, 
	CoreConverterPriority priority = CoreConverterPriority::Normal, 
	int processorAffinity = 1
)
```

**F#**<br />
``` F#
member ConvertToWav : 
        inFile : FileInfo * 
        outFile : string * 
        bitDepth : WavBitdepth * 
        frequency : WavFrequency * 
        channels : WavChannelMode * 
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
&nbsp;<dl><dt>inFile</dt><dd>Type: System.IO.FileInfo<br />The file to convert.</dd><dt>outFile</dt><dd>Type: System.String<br />The output filepath.</dd><dt>bitDepth</dt><dd>Type: <a href="T_DevCase_Core_Multimedia_WavBitdepth">DevCase.Core.Multimedia.WavBitdepth</a><br />The bit depth.</dd><dt>frequency</dt><dd>Type: <a href="T_DevCase_Core_Multimedia_WavFrequency">DevCase.Core.Multimedia.WavFrequency</a><br />The frequency.</dd><dt>channels</dt><dd>Type: <a href="T_DevCase_Core_Multimedia_WavChannelMode">DevCase.Core.Multimedia.WavChannelMode</a><br />The channel mode.</dd><dt>dspEffects (Optional)</dt><dd>Type: <a href="T_DevCase_ThirdParty_DBpoweramp_CoreConverterDspEffect">DevCase.ThirdParty.DBpoweramp.CoreConverterDspEffect</a><br />The CoreConverter DSP effects.</dd><dt>preserveTags (Optional)</dt><dd>Type: System.Boolean<br />Indicates whether the file should preserve tags after conversion.</dd><dt>priority (Optional)</dt><dd>Type: <a href="T_DevCase_ThirdParty_DBpoweramp_CoreConverterPriority">DevCase.ThirdParty.DBpoweramp.CoreConverterPriority</a><br />The CoreConverter.exe process priority.</dd><dt>processorAffinity (Optional)</dt><dd>Type: System.Int32<br />The amount of processors used by CoreConverter.exe.</dd></dl>

#### Return Value
Type: Int32<br />The process exit code.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_DBpoweramp_Converter">Converter Class</a><br /><a href="Overload_DevCase_ThirdParty_DBpoweramp_Converter_ConvertToWav">ConvertToWav Overload</a><br /><a href="N_DevCase_ThirdParty_DBpoweramp">DevCase.ThirdParty.DBpoweramp Namespace</a><br />