# Full API integration

Method 1:
1. At boot request ENG hero list + user language hero list
2. When a hero is added to the users rosters request additional info for that character (camping + skills) and store them with users heroes list (slightly slower than  the current local database method)
3. During calculation use the data stored on user's side

note: if the data is updated on EpicSeven DB the user has to remove and add the character again to make the changes effective

some Hero icons are missing on EpicSevenDB

Method 2:
Require all the data during boot -> longer startup time
