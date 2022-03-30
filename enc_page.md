
## Design a Secure Encrypted File Storage Service on Public Servers

**Project description:** The goal of the project was to be able to store files on a public server called "Datastore," in such a fashion that users could have a guarantee that the files they were storing were secure from adversaries and that they would not try and decrypt files that had been tampered with.


### Initial Design

This sketch shows the initial ideas for how the project would take advantage of different encryption schemes such that users could store, retrieve, delete, and share files with other users and avoid any eavesdropping or file tampering from adversaries. Public keys could be stored on a public server called "Keystore" without fear of tampering.

<img src="images/enc_scheme.jpg?raw=true"/>
