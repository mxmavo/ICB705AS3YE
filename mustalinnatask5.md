# MUSTA LINNA


## x) Read and summarize

answer here


## a) Pubkey today. Explain how you have used public key cryptography today or yesterday, outside of this homework. In addition to naming the system, identify how different parties use keys in different steps of the system. (Answering this question likely requries finding sources on your own. This subtask does not require tests with a computer.)


Yesterday I used SSH to connect from my laptop to my web server at janutex.com. When I connected the server and my laptop first did a Diffie Hellman key exchange. 

ssh user@janutex.com

Each side sent the other a temporary public key, and both used them to calculate the same shared secret, which then encrypted the session. The server proved it was really janutex.com by signing the exchange with its private host key.

~/.ssh/known_hosts

My laptop checked that signature with the server's public host key, which it had saved in known_hosts the first time I connected. Then I proved who I was by signing a message with my private key, which never leaves my laptop. The server checked that signature with my public key, which I had added to its authorized_keys file earlier. 

Because of this, I could log in securely without sending a password over the network.


## b) Encrypt and decrypt a message. Explain how different parties use different keys at different stages of operation. Evaluate the security of the tool you've chosen.


answer here


## c) Password management. Demonstrate use of a password manager. What kind of attacks take advantage of people not using password managers? (You can use any password manager, some examples include pass and KeePassXC.)


answer here

