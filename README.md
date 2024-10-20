# Gameoflife
The function was created using JavaScript and tested using unit tests in Jest. 
The function applies the following rules:
1. Any live cell with fewer than two live neighbours dies as if by under population.
2. Any live cell with more than three live neighbours dies, as if by overcrowding.
3. Any live cell with two or three live neighbours lives on to the next generation.
4. Any dead cell with exactly three live neighbours becomes a live cell.
“Live” or “Dead” cells can be represented with suitable values of either the appropriate text 
string, or 1 and 0 or true and false. If choosing just to write tests the provided code will use the 
text strings “Live” and “Dead”.
