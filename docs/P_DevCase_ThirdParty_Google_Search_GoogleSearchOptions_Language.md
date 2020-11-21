# GoogleSearchOptions.Language Property 
 

Gets or sets a value to restrict search results to pages in the specified language. If there are no results In the specified language, the search appliance displays results In all languages. 

 Default value: <a href="T_DevCase_Core_NET_GoogleLanguage">Auto</a>

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Google_Search">DevCase.ThirdParty.Google.Search</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[DefaultValueAttribute(typeof(GoogleLanguage), "Auto")]
public virtual GoogleLanguage Language { get; set; }
```

**VB**<br />
``` VB
<DefaultValueAttribute(GetType(GoogleLanguage), "Auto")>
Public Overridable Property Language As GoogleLanguage
	Get
	Set
```

**VB Usage**<br />
``` VB Usage
Dim instance As GoogleSearchOptions
Dim value As GoogleLanguage

value = instance.Language

instance.Language = value
```

**C++**<br />
``` C++
public:
[DefaultValueAttribute(typeof(GoogleLanguage), L"Auto")]
virtual property GoogleLanguage Language {
	GoogleLanguage get ();
	void set (GoogleLanguage value);
}
```

**F#**<br />
``` F#
[<DefaultValueAttribute(typeof(GoogleLanguage), "Auto")>]
abstract Language : GoogleLanguage with get, set
[<DefaultValueAttribute(typeof(GoogleLanguage), "Auto")>]
override Language : GoogleLanguage with get, set
```


#### Property Value
Type: <a href="T_DevCase_Core_NET_GoogleLanguage">GoogleLanguage</a><br />\[Missing <value> documentation for "P:DevCase.ThirdParty.Google.Search.GoogleSearchOptions.Language"\]

## Remarks
<a href="https://developers.google.com/custom-search/docs/xml_results#lrsp" target="_blank">https://developers.google.com/custom-search/docs/xml_results#lrsp</a>

## See Also


#### Reference
<a href="T_DevCase_ThirdParty_Google_Search_GoogleSearchOptions">GoogleSearchOptions Class</a><br /><a href="N_DevCase_ThirdParty_Google_Search">DevCase.ThirdParty.Google.Search Namespace</a><br />