# siteinfo
Demonstration code for the . 
 A new form text field named "Site API Key" needs to be added to the "Site Information" form with the default value of “No API Key yet”.
 When this form is submitted, the value that the user entered for this field should be saved as the system variable named "siteapikey".
 A Drupal message should inform the user that the Site API Key has been saved with that value.
 When this form is visited after the "Site API Key" is saved, the field should be populated with the correct value.
 The text of the "Save configuration" button should change to "Update Configuration".
 This module also provides a URL that responds with a JSON representation of a given node with the content type "page" only if the previously submitted API Key and a node id (nid) of an appropriate node are present, otherwise it will respond with "access denied".

Installation
-------------------------

Download into `sites/all/modules` and install.

How To Configure
-------------------------
Go to admin/config/system/site-information.
Enter Site Api Key.

How To Use
-------------------------


* Go to <Site Domain>/page_json/<Api key>/<node id> to see the endpoint.

