# cub3d_shl13
cub3d project 

### 20210630 

no libft / src / bonus files 

execute it by 
```
./cub3d maps/basic.cub
```
or 
```
./cub3d_bonus maps/bonus.cub
```
on terminal 


20210209 17:49
The default branch has been renamed!
main is now named master




  # Bonus 
  
• Wall collisions. 

• Ability to look up and down.

• Object collisions.

• Sounds and music. 

• More items in the maze.

• Earning points and/or losing life by picking up objects/traps.

![alt text](https://github.com/shl13/cub3d_shl13/blob/master/screenshot.bmp?raw=true)
!\[ alt text](https://github.com/[username]/[reponame]/blob/[branch]/image.jpg?raw=true)

  
  # Common Instructions

- Norm check must
- segmentation fault, bus error, double free NOPE
- must be freed check leaks cub3d
- Makefile -Wall -Wextra -Werror and no relink
- $(NAME) all clean fcelan re should be contained rules
- to turn in bonuses rule bonus included, must be in a different file _bonus.{c/h} done separately
- libft, copy and its Makefile in a 'libft'folder.
- test program test encouraged, though not be sumitted or graded
- submit to git repository.

# **Mandatory part - cub3D**

**Program name : cub3D
Turn in files : All your files
Makefile : all clean fclean re bonus
Arguments : a map in format *.cub**

**External functs.**

**Libft authorized**       Yes

**Description**

The constraints are as follows:

- use miniLibx. either the version that is available on os or from its sources. same rule for your libft.
- the management of your window must remain smooth

check if minimizing, changing to another window 

- display different wall texture NSEW
- display sprite instead of wall
- set floor and ceiling color two different ones
- if '—save' argument then bmp format save the first rendered image

- if no second argument, display image in a window with...
- → left and right arrow keys look left and right
- → WASD keep to move
- → ESC to quit
- → red cross to quit
- → if greater size comes in, size set depending on current display resolution
- → use images of minilibx strongly recommended

Your program must take as a first argument a scene description .cub extension 

- 4 possible characters on map : 012 and NSEW
- closed and surrounded by walls
- many empty lines ok except map
- many spaces ok except map
- map content always come last but other elements order mixed
- map must be parsed like the file (꼭 반듯한 직사각형 놉)

each element means.. 

Resolution R 

north texture NO

south texture SO

west texture WE

east texture EA

sprite texture S 

floor color F

ceiling color C 

0~255 range

if error, then "Error\n"and message of your choice
