# LZ77-Encoding-and-Decoding
<h3>Algorithm</h3>
<h4>LZ77 Encoding-Algorithm</h4>
● Find the longest match in the window for the lookahead buffer.
● If a match is found, output the pointer P. Move the coding position (and the window) L
bytes forward.
● If a match is not found, output a null pointer and the first byte in the lookahead buffer.
Move the coding position (and the window) one byte forward.
● If the lookahead buffer is not empty, return to step 2.
<h4>LZ77 Decoding-Algorithm</h4>
● Reverse the method used in encoding to generate the sequences.
● Do this operation using <encodedNumbers, encodedSizes, encodedLetters.>
<h5>LZ77 Encoding Example:</h5>
Input: “cabracadabrarrarrad”
Window Size: 13
Search Window Size: 7
Preview/Lookup Window Size: 6
