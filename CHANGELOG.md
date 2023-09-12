CHANGELOG
=========

1.7, 2023-08-06
---------------
- improve hero parsing regex for spell scrolls in inventory (issue #1)
- improve hero parsing regex for combination artifacts in Horn of the Abyss (issue #1)
- avoid needless serialization on opening first hero
- skip saving artifact spells as available if detectably banned by map
- fix not showing index on changing game version if no heroes parsed
- fix escaping special characters in exported HTML search bar
- improve compatibility between different Python major and minor versions


1.6, 2023-03-28
---------------
- add hero CSV/HTML export
- show donned artifact stats
- improve hero parsing regex


1.5, 2023-02-24
---------------
- add category toggles to hero index
- drop obsolete auto-load option


1.4, 2023-02-21
---------------
- add hero index page


1.3, 2023-02-22
---------------
- add hero charsheet view
- add recent heroes menu
- add separate toolbar for selected hero
- improve hero parsing regex
- make "movement points in total" read-only, as the game overwrites it on each turn
- save backup only if not already saved for current date
- fix not saving backup before overwriting


1.2, 2023-02-07
---------------
- add undo-redo command history dialog
- add toolbar button to open savefile folder
- add "Show unsaved changes" to edit-menu
- improve hero parsing regex
- improve tracking updates in hero primary attributes from artifact change
- fix army paste retaining previous values in new blank slots
- fix army SpinCtrl hidden arrows becoming visible on system colour change


1.1, 2023-01-29
---------------
- support multiple hero tabs
- show donned artifact stats
- fix using wx locale in Py2


1.0, 2022-01-20
---------------
- first public release