# CoreConverterDspEffect Enumeration
 

Specifies a `CoreConverter.exe` DSP effect

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_DBpoweramp">DevCase.ThirdParty.DBpoweramp</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public enum CoreConverterDspEffect
```

**VB**<br />
``` VB
Public Enumeration CoreConverterDspEffect
```

**VB Usage**<br />
``` VB Usage
Dim instance As CoreConverterDspEffect
```

**C++**<br />
``` C++
public enum class CoreConverterDspEffect
```

**F#**<br />
``` F#
type CoreConverterDspEffect
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.ThirdParty.DBpoweramp.CoreConverterDspEffect.None">**None**</td><td>0</td><td>Any DSP effect.</td></tr><tr><td /><td target="F:DevCase.ThirdParty.DBpoweramp.CoreConverterDspEffect.DeleteOutputFileOnError">**DeleteOutputFileOnError**</td><td>1</td><td>Deletes failed converted file.</td></tr><tr><td /><td target="F:DevCase.ThirdParty.DBpoweramp.CoreConverterDspEffect.DeleteSourceFileAfterConversion">**DeleteSourceFileAfterConversion**</td><td>2</td><td>Deletes source file after conversion.</td></tr><tr><td /><td target="F:DevCase.ThirdParty.DBpoweramp.CoreConverterDspEffect.RecycleSourceFileAfterConversion">**RecycleSourceFileAfterConversion**</td><td>4</td><td>Sends source file to recycle bin after conversion.</td></tr><tr><td /><td target="F:DevCase.ThirdParty.DBpoweramp.CoreConverterDspEffect.RemoveVoice">**RemoveVoice**</td><td>8</td><td>Removes voice from file.</td></tr><tr><td /><td target="F:DevCase.ThirdParty.DBpoweramp.CoreConverterDspEffect.RemoveInstrument">**RemoveInstrument**</td><td>16</td><td>Removes instruments from file.</td></tr><tr><td /><td target="F:DevCase.ThirdParty.DBpoweramp.CoreConverterDspEffect.Reverse">**Reverse**</td><td>32</td><td>Reverses complete audio file.</td></tr><tr><td /><td target="F:DevCase.ThirdParty.DBpoweramp.CoreConverterDspEffect.WriteSilence">**WriteSilence**</td><td>64</td><td>Writes a silence at start of file.</td></tr></table>

## See Also


#### Reference
<a href="N_DevCase_ThirdParty_DBpoweramp">DevCase.ThirdParty.DBpoweramp Namespace</a><br />