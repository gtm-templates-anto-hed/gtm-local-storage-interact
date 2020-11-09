# Local Storage Interact
A new Google Tag Manager template to manage items on Local Storage

## Description
This template allows you to easily interact with the Local Storage, set, get, remove or check if an item is present!

### Specification
To interact with the Local Storage, You must allow the Accesses Local Storage by specifying the settings in the permission tab. The name of the key in Local Storage must be exact to the name used in the field Key. More information: https://developers.google.com/tag-manager/templates/permissions#set_cookies

In Google Tag Manager, Click on Templates and Search Gallery and search the tag : Local Storage Interact  

To allowed Keys in Accesses Local Storage


1 - On GTM

2 - Click on : Templates

3 - Click on : Tag Template // Local Storage Interact

4 - Click on : Persmissions

5 - Click on : Accesses Local Storage

6 - Click on : Add Key

7 - Fill : The Key that you want to store or read

### More informations about Local Storage
https://www.w3schools.com/html/html5_webstorage.asp

### Setup
| Action | Description| Requirements| Success
| ------------- | ------------- | ------------- | ------------- |
| Set  | Allow you to stock key/value in Local Storage | Requires write access for the key | item set in Local Storage |
| Get  | Allow you to get value of a key in Local Storage | Requires read access for the key | item get from Local Storage |
| Remove  | Allow you to delete an item key/value in Local Storage | Requires write access for the key | item removed from Local Storage |
| Check  | Allow you to check if a value is already present in Local Storage | Requires write access for the key | Return a dataLayer push with "alreadyInLocalStorage" if the value of the key if already stocked in Local Storage. |

More information: https://antoine-hervillard.com/gtm-template-tag-local-storage-interact/
