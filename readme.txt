an example for a manifest v3,  
lite adblock-like web-extension,  
with both hiding rules that loads up very early (before rendering),  
as well as blocking rules.  

it should also save you some harsh rendering and even traffic,  
the main purpose is to reduce your context-switch and help your focus.  

note that this web-extension DOES NOT  
actually blocks one ad or another,  
please edit both 'at_document_start.css'  
and 'ruleset_001.json'  
with CSS rules,  
and regular-expressions (examples are provided) blocking rules.  
the manifest itself is somewhat of a premissive with permissions, that's fine for yourself.

feel free to fork and modify, 
no credit is needed. 
there are no javascript files nor bottlenecks that will slow you down here,  
there are no buttons, swithces, or fancy menues,  
it justs injects some css and has a "firewall" properties.

note that blocking rules string, for each rule is limited in length,  
so if you get an error telling you it is too long (more then 3KB afaik),  
just create a new rule (new id!) and move around stuff until each is short enough for your browser..

this web-extension protects, and respects your privacy, no analytics.  

public domain. the unlicensed.



=-=-=-=-=

there are no releases, you don't need those in here, 


just download the branch 'zip' using,  
https://github.com/314dk4r4k0/lite_adblock_a_manifest_v3_example/archive/refs/heads/master.zip  
unpack it, and load it as an unpacked web-extension from the 'chrome://extensions/' page  
(or 'edge://extensions/' page.. etc..), you can probably load it for firefox somehow too.. :|  




this repository was created to help with migration from manifest v2,  
take a look in here:  

https://gist.github.com/314dk4r4k0/0fe2ca5c668b1e8101e1206f10f0daae#file-re-enable-ublock-origin-and-all-manifest-v2-web-extensions-md  

