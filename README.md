### Trinket to Car interaction


This code is an example of the interaction between a car trinket and a car.
It implements the Diffie-Hellman handshake protocol for setting a secret key. 

After that, at the request from the key, the car sends a challenge(random number), which trinket must encrypt using the secret key and md5 hash, and send back. If the hash is correct, the machine will open.

Each step of the algorithm is written to console, from where you can track all actions.

For now, all parameters is written right into the code, so for launching you just have to cd in directory where you unpack project, and run it.

```sh
$ cd /TechnoParkHW2
$ cargo run
```
