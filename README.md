# ciphers_assignment
Deciphering text that is ciphered using Caesar, Vigenere or Playfair ciphers using a mix of python and C for my network security module assignment

*Please note that to run the notebook, the files ‘playfaircrack.c’ and ‘qgr.h’ should be downloaded in the same directory as the notebook for the Playfair cipher to work. 

*Also not that running the Playfair decipher might result in a different key than the one in this document since the Simulated Annealing algorithm randomly and iteratively changes the key a lot of times and the key might end up in a different local minimum. However, the plaintext should be very close every time.


Some helpful resources:

<li>Letter frequency: https://en.wikipedia.org/wiki/Letter_frequency</li>
<li>Index of Coincidence (IC): https://en.wikipedia.org/wiki/Index_of_coincidence</li>
<li>Determine cipher based on IC: https://www.nku.edu/~christensen/1402%20Friedman%20test%202.pdf</li>
<li>Determing if a cipher is playfair: https://artofproblemsolving.com/community/c1671h1005783_recognizing_that_a_cipher_is_a_playfair_cipher</li>
<li>Chi-squared: http://practicalcryptography.com/cryptanalysis/text-characterisation/chi-squared-statistic/</li>
<li>Vigenere cryptoanalysis concept : http://practicalcryptography.com/cryptanalysis/stochastic-searching/cryptanalysis-vigenere-cipher/</li>
<li>Shannon book on cryptography and python https://kaliboys.com/wp-content/uploads/2020/11/Implementing-cryptography-using-python.pdf</li>
<li>Quadgrams and english values http://practicalcryptography.com/cryptanalysis/text-characterisation/quadgrams/</li>
<li>Simulated Annealing algorithm https://towardsdatascience.com/optimization-techniques-simulated-annealing-d6a4785a1de7</li>

