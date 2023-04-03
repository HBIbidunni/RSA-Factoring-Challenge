# RSA Factoring Challenge
------

This Challenge involves an attempt to generate and factorize large enough prime numbers sniffed from an unsecured network as fast as possible before the target fixes this bug on their server. This is crucial in order to be able to decode the encrypted documents the target has.


<b>Clock_ticking ~ Time is of essence here!</b>


## More Information on RSA and Prime Factorization

`RSA` is named after its inventors: <b>Ron Rivest</b>, <b>Adi Shamir</b>, and <b>Leonard Adleman</b> and it is a widely used `encryption algorithm` that relies on the mathematical properties of large prime numbers.

`RSA encryption` involves the use of a <b>public key</b> and a <b>private key</b>. The <b>public key</b> can be freely distributed to anyone who wants to send an encrypted message, while the<b>private key</b> is kept secret by the recipient and used to decrypt the message.

## The link between RSA and Prime Factorization

* The link between prime factorization and RSA lies in the fact that RSA encryption relies on the difficulty of factoring large composite numbers into their prime factor

## Steps taken to generate the Public and Private Keys in RSA

* To encrypt a message using RSA encryption, the sender first converts the message into a numerical representation, typically by using the ASCII or Unicode codes for the characters. The sender then applies the public key to the numerical representation of the message to obtain an encrypted message. To decrypt the encrypted message, the recipient applies the private key to the encrypted message

## The Security of the RSA and Prime Factorization

* The security of RSA encryption relies on the fact that it is computationally difficult to factor large composite numbers into their prime factors
* This means that an attacker who intercepts an encrypted message and knows the public key cannot easily compute the corresponding private key and decrypt the message
* The security of RSA encryption is based on the assumption that no efficient algorithm exists for factoring large composite numbers
* It is important to note that the security of the RSA encryption is not absolute due to advances in computing power and new algorithms

---> It is highly evident, `Prime Factorization` is an important component of `RSA encryption`
