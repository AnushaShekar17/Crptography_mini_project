# PLAYFAIR_CIPHER_TEXT
4.3 Algorithm Explanation
Playfair Encryption Algorithm
1.
Enter the plaintext and keyword.
2.
Convert keyword to uppercase and remove duplicates.
3.
Generate the 5×5 Playfair matrix.
4.
Prepare plaintext by forming digraphs (pairs), replacing repeated letters with ‘X’.
5.
For each pair:
o
Same row → shift right
o
Same column → shift down
o
Rectangle → swap columns
6.
Combine all encrypted pairs to form the final ciphertext.
Playfair Decryption Algorithm
1.
Convert ciphertext to uppercase.
2.
Generate the 5×5 matrix using the same keyword.
3.
Split ciphertext into digraphs.
4.
For each pair:
o
Same row → shift left
o
Same column → shift up
o
Rectangle → swap columns
5.
Combine results to get plaintext.
4.2 Dataset
