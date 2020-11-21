# GoogleSearchResult.Title Property (Encoding, Encoding)
 

Gets the search result title in the specified text encoding.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Google_Search">DevCase.ThirdParty.Google.Search</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
public virtual string this[
	Encoding inEnc,
	Encoding outEnc
] { get; }
```

**VB**<br />
``` VB
Public Overridable ReadOnly Property Title ( 
	inEnc As Encoding,
	outEnc As Encoding
) As String
	Get
```

**VB Usage**<br />
``` VB Usage
Dim instance As GoogleSearchResult
Dim inEnc As Encoding
Dim outEnc As Encoding
Dim value As String

value = instance.Title(inEnc, outEnc)

```

**C++**<br />
``` C++
public:
virtual property String^ Title[Encoding^ inEnc, Encoding^ outEnc] {
	String^ get (Encoding^ inEnc, Encoding^ outEnc);
}
```

**F#**<br />
``` F#
abstract Title : string with get
override Title : string with get
```


#### Parameters
&nbsp;<dl><dt>inEnc</dt><dd>Type: System.Text.Encoding<br />The source text encoding.</dd><dt>outEnc</dt><dd>Type: System.Text.Encoding<br />The target text encoding.</dd></dl>

#### Property Value
Type: String<br />The search result title in the specified text encoding.

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Google_Search_GoogleSearchResult">GoogleSearchResult Class</a><br /><a href="Overload_DevCase_ThirdParty_Google_Search_GoogleSearchResult_Title">Title Overload</a><br /><a href="N_DevCase_ThirdParty_Google_Search">DevCase.ThirdParty.Google.Search Namespace</a><br />