# NewNote
# Commits
 - Commit 4/5:
 - solved problem/issue :
 - we were unable to count the prev list's items properly when we created new lists and tried adding new list items in prev list
 - Commit 5/6: 
 - changed the implementation (from array of numbers to array of objects) for both   notes and lists.Also had to create separate functions for displaying which is called by all other functions .(previously html string was concatenated/appended and used in addNote() or addList()..but now used in separate functions named displayNote()  - and displayList())

# Features
 -  A title bar showing no of lists created and no of notes created
 -  2 containers/columns one for notes and other for todo lists
 -  Stores notes as cards
 -  Set alarm or reminder
 -  Store all data in local storage
 -  Paste or type text into textbox and convert instantly into a note or a list

 # Problems
 - If u create notes very fast there is a delay in audio
 - sometimes audio does not work
 - time reminder is limited to hours of a day only

 # Could be added
  - If u tick a checkbox then that list item goes down/becomes faint colored
  - ticking all list items in a list shall delete the list
  - Convert typed note to image or pdf
  - ability to upload files from the device and open them in the webpage
  - draw using pen
  - change order of notes/cards
  - audio recorder
  - Multiple Themes(with variable fonts,sizes and colors)
