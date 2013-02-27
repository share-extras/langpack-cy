Alfresco Welsh Language Pack
============================

Author: Will Abson

This language pack provides translation of all the current web 
client message strings as well as all translatable repository
messages.

The translation is complete as of Alfresco Enterprise version 3.1 and
should be backwards-compatible with all previous versions.

All translations have been spell-checked using the Welsh dictionary
files for OpenOffice.org and manually checked for grammatical errors. 
As part of the project it has been necessary to standardise the 
translation of many of the terms used in the Alfresco interface, 
which have been documented in the file [glossary.txt](glossary.txt).

Installation and Usage
----------------------

Extract the contents of the ZIP file directly into 
`<TOMCAT_HOME>/shared/classes`. The appropriate directory structure 
should automatically be created.

You will need to restart the Alfresco server to load the language pack.

To use the language pack in the Alfresco Explorer web client you will 
need to add the 'cy' locale to the list of additional languages 
displayed on the login screen in `web-client-config-custom.xml`.

Alfresco Share will auto-detect the client language based on your 
browser settings. You will need to add 'Welsh' as the first entry in 
your preferred languages - in Firefox click _Tools > Options > Content > 
Languages > Choose_.

Note: TinyMCE translations (including Welsh) are available from the
[http://tinymce.moxiecode.com/download_i18n.php](TinyMCE Language Packs) page. You will need to 
install these into the `alfresco` and `share` webapps in order to
use TinyMCE as without a language pack for the current locale
TinyMCE will not work.

 * Web client: `alfresco/scripts/tiny_mce`
 * Share: `share/modules/editors/tiny_mce`

Thanks
------

The following sources have been instrumental in helping to develop 
the translation:

 * [http://www.kyfieithu.co.uk/kywiro/index.php](Kywiro) by Kevin Donnelly - provided searchable translations of all
   the major open source Welsh translations

 * The Welsh Language Board's [http://www.e-gymraeg.co.uk/bwrdd-yr-iaith/termau/Default.aspx](National Database of Terms)

 * The BBC [http://www.bbc.co.uk/wales/learnwelsh/](Learn Welsh) dictionary, grammer checker and guides

 * Mark H. Nodine's [http://www.cs.cf.ac.uk/fun/welsh/LexiconForms.html](searchable lexicon of Welsh words)

