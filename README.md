# honey-encryption


Honey encryption is a new encryption scheme that provides resilience against brute force attacks by ensuring that messages decrypted with invalid keys yield a valid-looking message. In this paper, we present our implementation of honey encryption and apply it to useful real-world scenarios such as credit cards and basic text messaging. We also extend the basic honey encryption scheme to support public-key encryption. Finally, we discuss the limitations we faced in our implementations and further requirements for strengthening our applications.

To run our test cases, run the two python scripts generic_alphabet_test.py and credit_card_test.py. For generic_alphabet_test.py, you can alter the alphabet and alphabet probabilities at the top of the script, and then encode and decode any alphabet string. For credit_card_test.py, you can alter the credit_card_example number, as well as the secret key used to encode and the guess key used to decode.


											
