<b>The css classes.</b>

<b>.board-wrapper</b> - container of the whole board set (game itself)<br>
<b>.board-wrapper .player</b> - name of the player (current turn)<br>
<b>table.board</b> - the playing board table

<b>table.board .row</b> - single row of the table (tr)<br>
<b>table.board #cell**</b> - select the cell in the table (board cell), use id for performance. All cells have their unique number (matrix style), so #cell11 is the first cell in the first row, #cell35 - row 3, cell 5<br>

<b>.sub-container</b> - the container that contains points and game progress data<br>
<b>.sub-container .title</b> - displays the content type of .sub-container<br>
<b>.sub-container .content</b> - content of the .sub-container<br>

Each board-wrapper has its own class name (e.g chess-board for chess, othello-board for othello), so customization of a single board set is not a problem

<b>** NOTE **</b>

The color scheme provided in the document was really ugly (e.g board has black and white squares and the pieces are black), so I decided to use a bit different colors,
which in my opinion are more user-friendly.

Also, the mobile blocks with points (.sub-container) position was changed, as usually users expect to see the game first, and then the points (more user-friendly interface).
