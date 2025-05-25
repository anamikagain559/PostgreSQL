What is the difference between the VARCHAR and CHAR data types?

Answer: 
The difference between VARCHAR and CHAR in SQL lies primarily in how they store and handle string data:

🔸 CHAR(n) – Fixed-Length String
Always stores exactly n characters.

If the input is shorter than n, it pads the remaining space with spaces.

Slightly faster for fixed-length data because the size is predictable.

🔸 VARCHAR(n) – Variable-Length String
Stores strings up to n characters.

Does not pad with spaces.

More storage-efficient for varying-length strings.

Slightly more overhead due to tracking the length of the string.