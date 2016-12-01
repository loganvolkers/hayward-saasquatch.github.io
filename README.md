# MORP Workshow Instructions

- Fork Repository as `yourGithubUsername.github.io`
- Fill in Tenant Alias in code snippet: 

```<script>!function(a,b){a("squatch","https://d2rcp9ak152ke1.cloudfront.net/assets/javascripts/v2/squatch.min.js",b)}(function(a,b,c){var d,e,f;c["_"+a]={},c[a]={},c[a].ready=function(b){c["_" + a].ready =  c["_" + a].ready || [];c["_" + a].ready.push(b);},e=document.createElement("script"),e.async=1,e.src=b,f=document.getElementsByTagName("script")[0],f.parentNode.insertBefore(e,f)},this);squatch.ready(function(){squatch.init({tenantAlias:"YOUR_TENANT_ALIAS_HERE",});squatch.widgets().createCookieUser({});});</script>```
- Paste code snippet into pages
- Add buttons to pages
 - Add `<div class="squatchpop"></div>` to add popup widget from div
 - Add `<button class="squatchpop">Referral Widget</button>` to add widget as button
- Add rules in Portal Settings page
