---
Date: 2024-10-04
---
Certainly. Here's the updated version with the requested changes:

The purpose of this article is to provide students who already know how to use Vim basics, but want to operate without leaving the keyboard in more situations.
Here we will summarize the most common scenarios.

Common shortcuts:
```plain
$ means last char of current line
0 means first index of current line
^ means first non-white space index of current line
gg means head of file
G means end of file
<c-f> next page
<c-b> prev page
try H M L 
w to next word first char
b when at middle of char, go to first char, when at first char, go to prev word
```

Jumping between brackets:
```plain
[[ //prev block
]] //next block 
]) ]} ]>
[( [{ [< //jump to next or prev second char
```

Swapping two lines:
```plain
ddp
```

![[./assets/Most Frequently Keybinding in Vim/Screen Recording 2024-10-04 at 21.09.20.mov]]

Inserting repeated code:
```plain
(repeat numbers) -> a -> (content) -> esc
```

![[./assets/Most Frequently Keybinding in Vim/Screen Recording 2024-10-04 at 21.14.04.mov]]

Deleting content inside brackets (large, medium, small, ", '):
```plain
d/c -> i -> (/[/{/"/' also back bracket works as well
```

![[./assets/Most Frequently Keybinding in Vim/Screen Recording 2024-10-04 at 21.19.41.mov]]

Auto-align:
```plain
(selection) -> =
```

![[./assets/Most Frequently Keybinding in Vim/Screen Recording 2024-10-04 at 21.28.22.mov]]