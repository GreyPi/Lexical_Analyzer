# Class Project

**Description:**

  My program is written in C++ and there are three files. The lexer.cpp, lexer.h, and Analyzer.h.
  The lexer.cpp is the main file and consists of calling the lexer.h and Analyzer.h. lexer.h goes 
  through the list and checks for tokens and lexemes. In the code I commented what number corresponds
  to what token variable. I use a vector of type int as my table to navigate through each state.
  After checking the contents of the file it assigns each token a number and then returns the number.
  Analyzer.h looks at the vector adds the values to the table. It sorts by seeing what is the end of the
  variable or not the end. Terminal or nonterminal. Finally I check the table and put some comments to try
  and show what x corresponds to y. At the end the value is returned to lexer.cpp and displayed.

**How to Run:**
  1. Download Zip folder.
  2. Extract files.
  3. Open the folder and write whatever you like to input.txt.
  4. Run lexer.exe.
  5. Now output.txt will display the token and lexeme of the input.

***Sources***: Professor Anthony Le of Cal State Fullerton University.
