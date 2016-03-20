Readme

Final Project
GDG x CAL 
Android for Beginners Study Jams
April 2016

Target: 18+

Reversi is a strategy board game for two players, played on an 6¡Ñ10 uncheckered board. There are sixty-four identical game pieces called disks (often spelled "discs"), which are light on one side and dark on the other. Players take turns placing disks on the board with their assigned color facing up. During a play, any disks of the opponent's color that are in a straight line and bounded by the disk just placed and another disk of the current player's color are turned over to the current player's color.

The object of the game is to have the majority of disks turned to display your color when the last playable empty square is filled.

Rules
Each of the disks' two sides corresponds to one player; they are referred to here as light and dark after the sides of Othello pieces, but any counters with distinctive faces are suitable. The game may for example be played with a chessboard and Scrabble pieces, with one player letters and the other backs.

The historical version of Reversi starts with an empty board, and the first two moves by each player are in the four central squares of the board. The players place their disks alternately with their color facing up and no captures are made. A players may choose to not play both pieces on the same diagonal, different from the standard Othello opening. It is also possible to play variants of Reversi and Othello wherein the second player's second move may or must flip one of the opposite-colored disks (as variants closest to the normal games).

For the specific game of Othello (as technically differing from the historical Reversi), the rules state that the game begins with four disks placed in a square in the middle of the grid, two facing white side up, two pieces with the dark side up, with same-colored disks on a diagonal with each other. Convention has initial board position such that the disks with dark side up are to the north-east and south-west (from both players' perspectives), though this is only marginally meaningful to play (where opening memorization is an issue, some players may benefit from consistency on this). If the disks with dark side up are to the north-west and south-east, the board may be rotated by 90¢X clockwise or counterclockwise. The dark player moves first.
	
a1	b1	c1	d1	e1	f1	g1	h1
a2	b2	c2	d2	e2	f2	g2	h2
a3	b3	c3	d3	e3	f3	g3	h3
a4	b4	c4	d4	e4	f4	g4	h4
a5	b5	c5	d5	e5	f5	g5	h5
a6	b6	c6	d6	e6	f6	g6	h6
a7	b7	c7	d7	e7	f7	g7	h7
a8	b8	c8	d8	e8	f8	g8	h8

Starting position
Dark must place a piece with the dark side up on the board, in such a position that there exists at least one straight (horizontal, vertical, or diagonal) occupied line between the new piece and another dark piece, with one or more contiguous light pieces between them. In the below situation, dark has the following options indicated by translucent pieces:

Chess zhor 22.png
Othello zver 22.png	
a1	b1	c1	d1	e1	f1	g1	h1
a2	b2	c2	d2	e2	f2	g2	h2
a3	b3	c3	d3	e3	f3	g3	h3
a4	b4	c4	d4	e4	f4	g4	h4
a5	b5	c5	d5	e5	f5	g5	h5
a6	b6	c6	d6	e6	f6	g6	h6
a7	b7	c7	d7	e7	f7	g7	h7
a8	b8	c8	d8	e8	f8	g8	h8

Where dark may play
After placing the piece, dark turns over (flips, captures) all light pieces lying on a straight line between the new piece and any anchoring dark pieces. All reversed pieces now show the dark side, and dark can use them in later moves¡Xunless light has reversed them back in the meantime. In other words, a valid move is one where at least one piece is reversed.

If dark decided to put a piece in the topmost location (all choices are strategically equivalent at this time), one piece gets turned over, so that the board appears thus:

a1	b1	c1	d1	e1	f1	g1	h1
a2	b2	c2	d2	e2	f2	g2	h2
a3	b3	c3	d3	e3	f3	g3	h3
a4	b4	c4	d4	e4	f4	g4	h4
a5	b5	c5	d5	e5	f5	g5	h5
a6	b6	c6	d6	e6	f6	g6	h6
a7	b7	c7	d7	e7	f7	g7	h7
a8	b8	c8	d8	e8	f8	g8	h8
Othello zver 22.png
Chess zhor 22.png
After dark play
Now light plays. This player operates under the same rules, with the roles reversed: light lays down a light piece, causing a dark piece to flip. Possibilities at this time appear thus (indicated by transparent pieces):

a1	b1	c1	d1	e1	f1	g1	h1
a2	b2	c2	d2	e2	f2	g2	h2
a3	b3	c3	d3	e3	f3	g3	h3
a4	b4	c4	d4	e4	f4	g4	h4
a5	b5	c5	d5	e5	f5	g5	h5
a6	b6	c6	d6	e6	f6	g6	h6
a7	b7	c7	d7	e7	f7	g7	h7
a8	b8	c8	d8	e8	f8	g8	h8
Othello zver 22.png
Chess zhor 22.png
Where light may play
Light takes the bottom left option and reverses one piece:

a1	b1	c1	d1	e1	f1	g1	h1
a2	b2	c2	d2	e2	f2	g2	h2
a3	b3	c3	d3	e3	f3	g3	h3
a4	b4	c4	d4	e4	f4	g4	h4
a5	b5	c5	d5	e5	f5	g5	h5
a6	b6	c6	d6	e6	f6	g6	h6
a7	b7	c7	d7	e7	f7	g7	h7
a8	b8	c8	d8	e8	f8	g8	h8
Othello zver 22.png
Chess zhor 22.png
After light play
Players take alternate turns. If one player can not make a valid move, play passes back to the other player. When neither player can move, the game ends. This occurs when the grid has filled up or when neither player can legally place a piece in any of the remaining squares. This means the game may end before the grid is completely filled. This possibility may occur because one player has no pieces remaining on the board in that player's color. In over-the-board play this is generally scored as if the board were full (64¡V0).

Example where the game ends before the grid is completely filled:

a1	b1	c1	d1	e1	f1	g1	h1
a2	b2	c2	d2	e2	f2	g2	h2
a3	b3	c3	d3	e3	f3	g3	h3
a4	b4	c4	d4	e4	f4	g4	h4
a5	b5	c5	d5	e5	f5	g5	h5
a6	b6	c6	d6	e6	f6	g6	h6
a7	b7	c7	d7	e7	f7	g7	h7
a8	b8	c8	d8	e8	f8	g8	h8

Vlasakova 1 ¡V 63 Schotte (European Grand Prix Prague 2011)
The player with the most pieces on the board at the end of the game wins. An exception to this is that if a clock is employed then if one player defaults on time that player's opponent wins regardless of the board configuration, with varying methods to determine the official score where one is required.

In common practice over the internet, opponents agree upon a time-control of, typically, from one to thirty minutes per game per player. Standard time control in the World Championship is thirty minutes, and this or something close to it is common in over-the-board (as opposed to internet) tournament play generally. In time-defaulted games, where disk differential is used for tie-breaks in tournaments or for rating purposes, one common over-the-board procedure for the winner of defaulted contests to complete both sides' moves with the greater of the result thereby or one disk difference in the winner's favor being the recorded score. Games in which both players have the same number of disks their color at the end (almost always with a full-board 32¡V32 score) are not very common, but also not rare, and these are designated as 'ties' and scored as half of a win for each player in tournaments. The term 'draw' for such may also be heard, but is somewhat frowned upon.

What are generally referred to as transcript sheets are generally in use in tournament over-the-board play, with both players obligated to record their game's moves by placing the number of each move in an 8¡Ñ8 grid. This both enables players to look up past games of note and tournament directors and players to resolve disputes (according to whatever specific rules are in place) where claims that an illegal move, flip or other anomaly are voiced. An alternative recording method not requiring a grid is also in use, where positions on a board are labeled left to right by letters a through h and top to bottom (far-to-near) by digits 1 through 8 (Note that this is the opposite of the chess standard, with numerals running upward away from the side (White) that has a through h left to right, and also that the perspective may be that of either player (with no fixed standard)), so that the very first move of a game may be (based upon standard starting setup) d3, c4, f5 or e6. This alternate notational scheme is used primarily in verbal discussions or where a linear representation is desirable in print, but may also be permissible as during-game transcription by either or both players.

Tournament play using ordinary sets rather than a computer interface¡Xwhere this can not be an issue¡Xhave various ways of handling illegal moves and over- or underflipping (flips that should not be made but are or should be but are not). For example, permitting either player (perpetrator or its opponent) to make a correction going back some fixed number of moves (after which no remedy is available) is one procedure that has been used.

Significant variants of the game, such as where the starting position differs from standard or the objective is to have the fewest pieces one's color at the end, are sometimes¡Xbut rarely¡Xplayed.

Reference
https://en.wikipedia.org/wiki/Reversi
