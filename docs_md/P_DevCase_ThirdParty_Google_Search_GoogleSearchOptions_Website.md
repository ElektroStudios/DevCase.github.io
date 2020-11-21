# GoogleSearchOptions.Website Property 
 

Gets or sets a value that allows you to restrict all search results should to a given site. 

 The specified value must contain less than <a href="F_DevCase_ThirdParty_Google_Search_GoogleSearchOptions_MaxWebsiteLength">MaxWebsiteLength</a> characters. 

 Default value: {null}

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Google_Search">DevCase.ThirdParty.Google.Search</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DefaultValueAttribute("")]
public string Website { get; set; }
```

**VB**<br />
``` VB
<DefaultValueAttribute("")>
Public Property Website As String
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As GoogleSearchOptions
Dim value As String

value = instance.Website

instance.Website = value
```

**C++**<br />
``` C++
public:
[DefaultValueAttribute(L"")]
property String^ Website {
	String^ get ();
	void set (String^ value);
}
```

**F#**<br />
``` F#
[<DefaultValueAttribute("")>]
member Website : string with get, set

```


#### Property Value
Type: String<br />\[Missing <value> documentation for "P:DevCase.ThirdParty.Google.Search.GoogleSearchOptions.Website"\]

## Remarks
<a href="https://developers.google.com/custom-search/docs/xml_results#as_sitesearchsp" target="_blank">https://developers.google.com/custom-search/docs/xml_results#as_sitesearchsp</a>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Google_Search_GoogleSearchOptions">GoogleSearchOptions Class</a><br /><a href="N_DevCase_ThirdParty_Google_Search">DevCase.ThirdParty.Google.Search Namespace</a><br />