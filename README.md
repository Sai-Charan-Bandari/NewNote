# NewNote
Commit 4/5:
solved problem/issue :
we were unable to count the prev list's items properly when we created new lists and tried adding new list items in prev list
Commit 5/6: 
changed the implementation (from array of numbers to array of objects) for both notes and lists.Also had to create separate functions for displaying which is called by all other functions .(previously html string was concatenated/appended and used in addNote() or addList()..but now used in separate functions named displayNote() and displayList())