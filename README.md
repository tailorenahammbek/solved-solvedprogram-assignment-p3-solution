Download Link: https://assignmentchef.com/product/solved-solvedprogram-assignment-p3-solution
<br>
Define Money class, which maintains two integer data fields, dollars and cents. Overload four arithmetic operators (+, -, *, /).

• The value of ‘cents’ never exceeds 99. If it exceeds, you must adjust the amount in ‘dollars’ accordingly.

• The value of ‘cents’ is always printed in two digits (use library). e.g., 05 cents, not 5 cents

• “dollar” is display instead of “dollars” when the dollar value is 1

• “cent” is display instead of “cents” when the cent value is either 1 or 0.

• – operator is define only when the left side is greater than or equal to right side. That is, use ‘assert’ function to guarantee this requirement. Requirements:

• You must provide “Makefile” for the separate compilation at Linux.

• Write the Money class (Money.h and Money.cpp) so that main.cpp works without any changes to produce the expected result (See below to run the demo) Turn-in: After you verify that your program runs on your Linux account, do as follows in the Linux account

• All your programs must be placed in p3 directory (folder). o Clean all object file (.o) and a.out if exist. o p3 directory should have the complete programs with header files (.h), source files (.cpp), main.cpp, and Makefile

• Compress files as follows (You must be in p3 folder) o zip p3Firstname.zip * (This is a Linux command)

• Transfer p3Firstname.zip (e.g., p3Hong.zip) to your computer and submit it via D2L (p3 dropbox of D2L). Demo program (in the Linux account) ~hs/demo/p3