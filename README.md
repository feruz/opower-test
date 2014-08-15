The css classes.

.board-wrapper - container of the whole board set (game itself)
.board-wrapper .player - name of the player (current turn)
table.board - the playing board table

table.board .row - single row of the table (tr)
table.board #cell** - select the cell in the table (board cell), use id for performance. All cells have their unique number (matrix style), so #cell11 is the first cell in the first row, #cell35 - row 3, cell 5

.sub-container - the container that contains points and game progress data
.sub-container .title - displays the content type of .sub-container
.sub-container .content - content of the .sub-container

Each board-wrapper has its own class name (e.g chess-board for chess, othello-board for othello), so customization of a single board set is not a problem

** NOTE **
The color scheme provided in the document was really ugly (e.g board has black and white squares and the pieces are black), so I decided to use a bit different colors,
which in my opinion are more user-friendly.

Also, the mobile blocks with points (.sub-container) position was changed, as usually users expect to see the game first, and then the points (more user-friendly interface).
