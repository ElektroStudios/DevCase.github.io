# GoogleSearchOptions.InputEncoding Property 
 

Gets or sets the input character encoding. 

 Default value: ISO-8859-1 (latin1)

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Google_Search">DevCase.ThirdParty.Google.Search</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DefaultValueAttribute(typeof(string), "ISO-8859-1")]
[TypeConverterAttribute(typeof(EncodingTypeConverter))]
public Encoding InputEncoding { get; set; }
```

**VB**<br />
``` VB
<DefaultValueAttribute(GetType(String), "ISO-8859-1")>
<TypeConverterAttribute(GetType(EncodingTypeConverter))>
Public Property InputEncoding As Encoding
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As GoogleSearchOptions
Dim value As Encoding

value = instance.InputEncoding

instance.InputEncoding = value
```

**C++**<br />
``` C++
public:
[DefaultValueAttribute(typeof(String), L"ISO-8859-1")]
[TypeConverterAttribute(typeof(EncodingTypeConverter))]
property Encoding^ InputEncoding {
	Encoding^ get ();
	void set (Encoding^ value);
}
```

**F#**<br />
``` F#
[<DefaultValueAttribute(typeof(string), "ISO-8859-1")>]
[<TypeConverterAttribute(typeof(EncodingTypeConverter))>]
member InputEncoding : Encoding with get, set

```


#### Property Value
Type: Encoding<br />\[Missing <value> documentation for "P:DevCase.ThirdParty.Google.Search.GoogleSearchOptions.InputEncoding"\]

## Remarks
<a href="https://developers.google.com/custom-search/docs/xml_results#iesp" target="_blank">https://developers.google.com/custom-search/docs/xml_results#iesp</a>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Google_Search_GoogleSearchOptions">GoogleSearchOptions Class</a><br /><a href="N_DevCase_ThirdParty_Google_Search">DevCase.ThirdParty.Google.Search Namespace</a><br />