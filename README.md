# WebSecurity-AES-Cryptography

Cryptography: 
The most issues in the web is security matters and because of keeping and transdering sensitive data in the web, So we must provide secure system on it. The most popular and practical way to establish secure connection in the web is cryptography techniques. Cryptography techs are the process of encryption and decryption data to keep data secure. For example in the below figure Bob wants to send data to Alice. This data is known as message and input parameter to cryptography process. Then specific key with encryption function will be added to this message and produced cipher text which is our encrypted message so this message goes through the network where hackers are waiting to rob this data.


Advanced Encryption Standard (AES)
AES is one of the cryptography techniques which uses same secret key and is on the Rijndael cipher algorithm. AES is based on substitution and permutation functions and uses complicated ways to produce strong and almost unbreakable key which is our aim in order to transmitting our sensitive data through the network.
At the first step AES expand key with the 128 bits length to more than ten key which each of these keys have 128 bits length, the number of produced key build variant cycles. Message as input parameter will be mixed with these keys. AES just uses “AddRoundKey” function in the K0  and in the Kn uses “SubBytes”, “Shiftrows” and AddRoundKey” and in the AES uses in the K2 to Kn-1 all of four functions “AddRoundKey”, “SubBytes”, “Shiftrows” and AddRoundKey”. Eventually message or plain text passes these complicated functions and will be converted to encrypted message or cipher text. 
AES uses this pattern inversely to produce same message from encrypted message. AES converts message text and key to four by four matrix, because of working by matrix form is more easier than original form. Look at below picture for having more clear imagination of what happens inside AES algorithm. 
