﻿Diplo Dictionary Editor for Umbraco
-----------------------------------

This is a custom section for editing Dictionary content in Umbraco. It allows simple editing of all dictionary items and also allows the dictionary to be exported and imported in CSV format.

Note: It only enables editing of dictionary items and doesn't allow new dictionary items to be created.

Important - Please Read
-----------------------

This package creates a new custom section in Umbraco called 'Dictionary Editor' when installed. 

As this is a new section then by default no users will have been given permission to view it. After installation the package attempts to grant permission to members of the "Admin" group (you may need to log in and out to see this).

However, for other users to see this new section you *must* explicitly grant them permission. This gives greater control over who can edit the Dictionary, but requires some post installation set-up. So don't be surprised after installation if you don't see the new section :)

To grant permissions in Umbraco 7.7 and up please do this:

* Go to the Users section in Umbraco and then select Groups from the top-right menu

* In groups create a new group and call it something like 'Dictionary Editor'

* Then, in the Assign access area of the group, go to Sections and click 'Add' and select 'Dictionary Editor' from the list

* Finally, in the Users tab select which users you wish to add to this new group

Note: You will (probably) need to log out and back in again from permissions to be applied. Once you have done so you should see the new section (with the globe icon) at the bottom of the Umbraco sections.

Reporting Issues
----------------

If you have any issues or feature requests then please post them on GitHub at:

https://github.com/DanDiplo/Diplo.DictionaryEditor/issues

You can also contact me via my website at https://www.diplo.co.uk/about/contact-me/

