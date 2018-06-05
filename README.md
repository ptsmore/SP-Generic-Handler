# SP-Generic-Handler

if error " Access to the path '\\your ip\sharepoint\DEV' is denied. "

Set Web.config in interpub
<pre>

<identity impersonate="true" userName="your spfarm user" password="..." />
    <authorization>
      <allow users="*" />
    </authorization>
   
</pre>
