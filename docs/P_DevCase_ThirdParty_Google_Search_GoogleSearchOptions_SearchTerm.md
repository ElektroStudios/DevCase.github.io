# GoogleSearchOptions.SearchTerm Property 
 

Gets or sets the search query. Note that whitespaces are automatically separated by a plus (+) sign 

 Default value: {null}

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Google_Search">DevCase.ThirdParty.Google.Search</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DefaultValueAttribute("")]
public string SearchTerm { get; set; }
```

**VB**<br />
``` VB
<DefaultValueAttribute("")>
Public Property SearchTerm As String
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As GoogleSearchOptions
Dim value As String

value = instance.SearchTerm

instance.SearchTerm = value
```

**C++**<br />
``` C++
public:
[DefaultValueAttribute(L"")]
property String^ SearchTerm {
	String^ get ();
	void set (String^ value);
}
```

**F#**<br />
``` F#
[<DefaultValueAttribute("")>]
member SearchTerm : string with get, set

```


#### Property Value
Type: String<br />\[Missing <value> documentation for "P:DevCase.ThirdParty.Google.Search.GoogleSearchOptions.SearchTerm"\]

## Remarks
<a href="https://developers.google.com/custom-search/docs/xml_results#qsp" target="_blank">https://developers.google.com/custom-search/docs/xml_results#qsp</a>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Google_Search_GoogleSearchOptions">GoogleSearchOptions Class</a><br /><a href="N_DevCase_ThirdParty_Google_Search">DevCase.ThirdParty.Google.Search Namespace</a><br />