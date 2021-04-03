# LZ77-Encoding-and-Decoding
<h3>Algorithm</h3>
<h4>LZ77 Encoding-Algorithm</h4>
● Find the longest match in the window for the lookahead buffer.<br>
● If a match is found, output the pointer P. Move the coding position (and the window) L
bytes forward.<br>
● If a match is not found, output a null pointer and the first byte in the lookahead buffer.
Move the coding position (and the window) one byte forward.<br>
● If the lookahead buffer is not empty, return to step 2.<br>
<h4>LZ77 Decoding-Algorithm</h4>
● Reverse the method used in encoding to generate the sequences.<br>
● Do this operation using <encodedNumbers, encodedSizes, encodedLetters.><br>
<h5>LZ77 Encoding Example:</h5>
Input: “cabracadabrarrarrad”<br>
Window Size: 13<br>
Search Window Size: 7<br>
Preview/Lookup Window Size: 6<br>
