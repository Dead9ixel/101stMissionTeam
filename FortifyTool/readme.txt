This folder is for fortify tool settings.
You must rename all filenames to initServer.sqf for the settings to work.

it is a string for the item name and a whole number integer for budget and cost.
Here is the basic setup.

[west, total budget,
[
["item_name", cost],
["item_name", cost]
]
]call acex_fortify_fnc_registerObjects;
