Ahmed Ullah
Date: 03.02.2023
------------------------------------
To check vim installed: vim (from  terminal)
To install vim: sudo apt install vim

------------------------------------
#### Short cut with example (All command
are from normal mood)
------------------------------------
```
A = cursor will go create and go a new line top of the current line
I = cursor will move start of the current line (from normal mood)
3 (any number) and press up/down arrow key (from normal mood, to go 3/any number line up/down)

k = up
j = bottom

10 k -> to of the 10th line

u = undo
crtl+r = redo

```
-------------------------------------
Install vim feature and add new feature
create vim rc file and paste 
all setting for permanant uses:

```
vi ~/.vimrc
-------------------------------------
set number (from command mood, to show number in terminal)
set relativenumber (relative number in terminal)
set number
set relativenumber
set tabstop=4
set shiftwidth=4
set autoindent
set mouse=a
colorscheme slate

```
-------------------------------
#### Visual mood (press exc then v) 
Shortcut
-------------------------------
```
d= delete (selected items)
D=delete rest of the line from current
25dd = delet next 25 lines
d10k= to delet top 10 lines
d10j= to delet bottom 10 lines

y=(yank) copy selected items
yy = to copy the whole line without select
10yy = copy the 10 lines

p=paste
P= paste top the current line
10p = paste 10 times
cc = cut the whole line without select
r=replace
u = word (even seperated by space,- will count as seperate word) 
W = word (if only seperated by _ will count as single word )
even seperated by space,- will count as seperate word) 
yiw = (yank in a word) to copy current word (put cursor any of the character of the word)
ciw = cut the word 

```
-------------------------------
#### To cut-and-paste or copy-and-paste:
-------------------------------
```
Position the cursor at the beginning of the text you want to cut/copy.
Press v to begin character-based visual selection, or V to select whole lines, or Ctrl-v or Ctrl-q to select a block.
Move the cursor to the end of the text to be cut/copied. While selecting text, you can perform searches and other advanced movement.
Press d (delete) to cut, or y (yank) to copy.
Move the cursor to the desired paste location.
Press p to paste after the cursor, or P to paste befor
```

----------------------------------------
#### Practice dummy text
----------------------------------------
#### What is Lorem Ipsum?
Lorem Ipsum is simply dummy text of the printing and ttypesetting ypesetting industry.
it is an unknown printer took a galley of type and scrambled it to make a type specimen book. 
It has test not only five centuries, but also the leap into electronic typesetting,
remaining essentially unchanged. It was popularised in the 1960s with the release of Letrase

#### What is Lorem Ipsum?
Lorem Ipsum is simply dummy text of the printing and ttypesetting ypesetting industry.
Lorem Ipsum has been the industry's standard dummy text ever since the 1500s, 
it is an unknown printer took a galley of type and scrambled it to make a type specimen book. 
It has test not only five centuries, but also the leap into electronic typesetting,
remaining essentially unchanged. It was popularised in the 1960s with the release of Letrase.
