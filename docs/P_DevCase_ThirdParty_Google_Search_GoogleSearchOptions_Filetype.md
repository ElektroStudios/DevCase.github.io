# GoogleSearchOptions.Filetype Property 
 

Gets or sets a value that allows you to restrict search results to documents with a particular file extension. 

 Default value: {null}

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Google_Search">DevCase.ThirdParty.Google.Search</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DefaultValueAttribute("")]
public string Filetype { get; set; }
```

**VB**<br />
``` VB
<DefaultValueAttribute("")>
Public Property Filetype As String
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As GoogleSearchOptions
Dim value As String

value = instance.Filetype

instance.Filetype = value
```

**C++**<br />
``` C++
public:
[DefaultValueAttribute(L"")]
property String^ Filetype {
	String^ get ();
	void set (String^ value);
}
```

**F#**<br />
``` F#
[<DefaultValueAttribute("")>]
member Filetype : string with get, set

```


#### Property Value
Type: String<br />\[Missing <value> documentation for "P:DevCase.ThirdParty.Google.Search.GoogleSearchOptions.Filetype"\]

## Remarks
<a href="https://developers.google.com/custom-search/docs/xml_results#as_filetypesp" target="_blank">https://developers.google.com/custom-search/docs/xml_results#as_filetypesp</a>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Google_Search_GoogleSearchOptions">GoogleSearchOptions Class</a><br /><a href="N_DevCase_ThirdParty_Google_Search">DevCase.ThirdParty.Google.Search Namespace</a><br />