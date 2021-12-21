# End-to-end encryption for a chatroom in python 📳
End-to-end encryption (E2EE) is a system of communication where only the
communicating users can read the messages. In principle, it prevents potential
eavesdroppers including telecom providers, Internet providers, and even the provider
of the communication service from being able to access the cryptographic keys
needed to decrypt the conversation.
<br>
This application uses RSA512 keypair. RSA (Rivest–Shamir–Adleman) is a
public-key cryptosystem that is widely used for secure data transmission. It is also one
of the oldest.

## Methods ang Logic
The developed app is a secure chat software made with Python 3. It is a secure
way of sending and receiving messages relayed by the server.
<br>
● It is end-to-end encrypted which means the server can't read what clients are
sending.
<br>
● It also generates a new RSA512 keypair for every client which is used to
identify him, this is useful for verification purposes as it prevents anyone else
from pretending he's someone else.
<br>
● The server is by default set to use localhost (127.0.0.1) IP address.
<br>
● If you want to use other IP (to connect outside your local machine), you need to
change IP in config.conf file.
