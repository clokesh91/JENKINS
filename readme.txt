Group - 4 
2017HV92509	M KUMAR	
2017HV92515	CHINTHAKUNTA LOKESH

Probelm Statement:
We will write a game called Decoder for beginner and advanced level.
A user is given 25 choices to guess the colors choosen by the computer. The computer first chooses five distinct colors from Red, Green, Blue, White, Black, Yellow, Pink, Orange, Cyan and Brown. The user can enter his or her choice of colors. The program will report the user's performance using colors. Red means no match, white means a match of color and black means positional match.

For example, assume the program has choosen the colors:
Red, Blue, White, Brown, Pink.

Here is a sequence of input from the user and the response from the
program:

Input								Response
Cyan, Brown, Pink, Green, Yellow	White, White, Red, Red, Red
Red, Brown, Pink, Blue, White		Black, White, White, White, White
Red, Blue, Brown, Pink, White		Black, Black, White, White, White
Red, Blue, White, Brown, Pink		Black, Black, Black, Black, Black

The program continues until either the user has cracked the code (guessed
correctly) or 25 chances run out.
Implement the beginner level where the generated colors are unique. Also implement the advanced level where repetition is allowed for several colors.
