Author: Aaron Phalen | Twitter: @aaron_phalen | Email: aaronphalen@gmail.com

#Useful Vi Editor Commands

1. :w --> save to a file
2. :q --> quit out of editor file
3. :q! --> quit out of editor without saving file
4. w --> move one word forward at a time in file
5. b --> move one word back at a time in file
6. :wq --> save file and quit editor
7. :1,5y --> yank (copy) lines 1 through 5
8. :1,5d --> cut lines 1 through 5
9. $ --> move to end of line in file
10. 0 --> move to the beginning of the line in file
11. H --> moves to top of file (think H for "high")
12. M --> moves to middle of file (think M for "middle")
13. L --> moves to low part of file (think L for "low")
14. ctrl + f --> move forward in file (autoscroll down)
15. ctrl + b --> move back in file (autoscroll up)
16. :45 --> move to line 45 in file
17. :/text --> search for occurences of text in file
18. G --> move to end of file
19. 2G --> move to 2nd line of file
20. a --> move cursor to the right one and enter editor into insert mode
21. I --> move to beginning of line and enter editor into insert mode
22. A --> move cursor to end of line and enter editor into insert mode
23. dd --> delete current line
24. d$ --> delete from current position to end of file
25. d0 --> delete from current position to beginning of file
26. u --> undo
27. ctrl + shift + r --> redo
28. vim -O <filename1> <filename2> --> open multiple files split vertically
29. ctrl + w + l --> move to right vertically split window
30. ctrl + w + h --> move to left vertically split window
31. :vertical resize 80 --> resize current window to 80 pixes width
32. :vertical resize +5 --> resize current window width by 5 pixes
33. o --> new line below cursor (think "open up" the text)
34. O --> new line above cursor (think "open up" the text editor)
35. ctrl +  v --> enter into visual mode
36. i --> enter into insert mode
37. :s/text1/text2/g --> replace all text1 with text2 in file on current line (think "global" for g)
38. :%s/text1/text2/g --> replace all text1 with text2 in file (think "global" for g)
39. :%s/text1/text2 --> replace first text1 with text2 in file
40. :s/text1/text2 --> replace first text1 with text2 in file on current line
41. ctrl + shift + p --> paste yanked or copied text
42: :set nu --> display line numbers in vim
43: set nonu --> turn off display line number
44. :set paste --> format text for paste into file
45. :set nopaste --> turn off format text for pasting
46. ctrl + v  + > --> shift selected lines one tab indentation
47. ctrl + v + shift + i + esc --> comment selected lines
48. ctrl + v + x --> uncomment selected lines
49. :%s/text1//g --> delete all occurrences of text1 file
50. :s/text1//g --> delete all occurrences of text1 in current line of file
51. :color blue --> change background color of screen to blue
52. :%s/search_word//gn --> count number of occurences of search_word in file
53. :s/search_word//gn --> count number of occurences of search_word in current line
54. :color blue --> changes vim color scheme to blue theme
55. :color default --> default vim color scheme to default theme
56. ctrl + shift + o (ctrl + O) --> return to previous location. Think "original" for O.

