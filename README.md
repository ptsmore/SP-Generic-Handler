# SP-Generic-Handler

if error " Access to the path '\\your ip\sharepoint\DEV' is denied. "

Set Web.config in interpub
<pre>
&lt;identity impersonate="true" userName="your spfarm user" password="..." /&gt;
    &lt;authorization&gt;
      &lt;allow users="*" /&gt;
    &lt;/authorization&gt;
</pre>
