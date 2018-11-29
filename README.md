# SP-Generic-Handler

-if you want to use "Handler ashx" with "SVC ISAPI" 
first you just unload that project and add "<TokenReplacementFileExtensions>ashx;svc</TokenReplacementFileExtensions>"
in Project.csproj and then reload it back

-if error " Access to the path '\\your ip\sharepoint\DEV' is denied. "

Set tag identity in Web.config in interpub
<pre>
&lt;identity impersonate="true" userName="your spfarm user" password="..." /&gt;
    &lt;authorization&gt;
      &lt;allow users="*" /&gt;
    &lt;/authorization&gt;
</pre>
