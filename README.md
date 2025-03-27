# A Primer for implementing the Post-Quantum Cryptography network 
Quantum Safe, Crypto-Agile P2P network for Crypto-Ledgers

![nist.jpeg](https://github.com/Tatsuru-Kikuchi/PQC/blob/main/NIST2.jpeg)

In recent years, there has been a substantial amount of research on quantum computers - machines that exploit quantum mechanical phenomena to solve mathematical problems that are difficult or intractable for conventional computers. If large-scale quantum computers are ever built, they will be able to break many of the public-key crypto systems currently in use. This would seriously compromise the confidentiality and integrity of digital communications on the Internet and elsewhere. The goal of post-quantum cryptography (PQC) is to develop cryptographic systems that are secure against both quantum and classical computers, and can interoperate with existing communications protocols and networks.

- One of the requirements for the validators is that the contents be served through the HTTPS protocol for security, using a current and secure version of TLS, using a valid certificate signed by a well-known certificate authority. 
- Another important requirements for the validator is providing a domain validation to all the participants in the Crypto-Ledger network to recognize who runs each validator by claiming both ownership of a validator key and ownership of the domain. 

To enhance the security against future attacks from quantum computers may be implemented by the Post-quantum TLS (PQTLS) which aims to secure the TLS protocol by implementing post-quantum cryptography, which uses quantum algorithms resistant to quantum attack.


