# YoutubeScopes Enumeration
 

Specifies the OAuthv2 scopes for use with the YouTube API.

**Namespace:**&nbsp;<a href="N_DevCase_ThirdParty_Google_Youtube">DevCase.ThirdParty.Google.Youtube</a><br />**Assembly:**&nbsp;DevCase.ThirdParty (in DevCase.ThirdParty.dll) Version: 3.3.0.0 (3.3)

## Syntax

**C#**<br />
``` C#
[FlagsAttribute]
public enum YoutubeScopes
```

**VB**<br />
``` VB
<FlagsAttribute>
Public Enumeration YoutubeScopes
```

**VB Usage**<br />
``` VB Usage
Dim instance As YoutubeScopes
```

**C++**<br />
``` C++
[FlagsAttribute]
public enum class YoutubeScopes
```

**F#**<br />
``` F#
[<FlagsAttribute>]
type YoutubeScopes
```


## Members
&nbsp;<table><tr><th></th><th>Member name</th><th>Value</th><th>Description</th></tr><tr><td /><td target="F:DevCase.ThirdParty.Google.Youtube.YoutubeScopes.Youtube">**Youtube**</td><td>2</td><td>Refers to the <a href="https://www.googleapis.com/auth/youtube" target="_blank">https://www.googleapis.com/auth/youtube</a> scope. 

 Manage your YouTube account. This scope is functionally identical to the ForceSSL because the YouTube API server is only available via an HTTPS endpoint. 

 As a result, even though this scope does not require an SSL connection, there is actually no other way to make an API request.</td></tr><tr><td /><td target="F:DevCase.ThirdParty.Google.Youtube.YoutubeScopes.ReadOnly">**ReadOnly**</td><td>4</td><td>Refers to the <a href="https://www.googleapis.com/auth/youtube.readonly" target="_blank">https://www.googleapis.com/auth/youtube.readonly</a> scope. 

 View your YouTube account.</td></tr><tr><td /><td target="F:DevCase.ThirdParty.Google.Youtube.YoutubeScopes.ForceSSL">**ForceSSL**</td><td>8</td><td>Refers to the <a href="https://www.googleapis.com/auth/youtube.force-ssl" target="_blank">https://www.googleapis.com/auth/youtube.force-ssl</a> scope. 

 Manage your YouTube account. 

 This scope requires communication with the API server to happen over an SSL connection.</td></tr><tr><td /><td target="F:DevCase.ThirdParty.Google.Youtube.YoutubeScopes.Partner">**Partner**</td><td>16</td><td>Refers to the <a href="https://www.googleapis.com/auth/youtubepartner" target="_blank">https://www.googleapis.com/auth/youtubepartner</a> scope. 

 View and manage your assets and associated content on Youtube.</td></tr><tr><td /><td target="F:DevCase.ThirdParty.Google.Youtube.YoutubeScopes.PartnerChannelAudit">**PartnerChannelAudit**</td><td>32</td><td>Refers to the <a href="https://www.googleapis.com/auth/youtubepartner-channel-audit" target="_blank">https://www.googleapis.com/auth/youtubepartner-channel-audit</a> scope. 

 View private information of your YouTube channel relevant during the audit process with a YouTube partner.</td></tr><tr><td /><td target="F:DevCase.ThirdParty.Google.Youtube.YoutubeScopes.Upload">**Upload**</td><td>64</td><td>Refers to the <a href="https://www.googleapis.com/auth/youtube.upload" target="_blank">https://www.googleapis.com/auth/youtube.upload</a> scope. 

 Upload YouTube videos and manage your YouTube videos.</td></tr></table>

## See Also


#### Reference
<a href="N_DevCase_ThirdParty_Google_Youtube">DevCase.ThirdParty.Google.Youtube Namespace</a><br />