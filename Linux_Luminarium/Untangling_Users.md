# Untangling Users
- Used the `ssh -i key hacker@pwn.college` command in the terminal to establish connection between the terminal and [pwn.college](https://pwn.college/)

## Becoming root with su
**Commands used:**
- `su`  : Used to allow the user to elevate privileges to root, it also checks to make sure that the user knows the root password

**Thought Process:**
- Need to read the `/flag` file to get the flag but to do that we need root privileges, which we get by using the `su` command and providing the root password.

**Solution:**
- Start the challenge, input the command `su` and enter the correct password "hack-the-planet" to switch user to root to be able to `cat /flag` and get the flag.  

**Flag Obtained:**
> *pwn.college{0IAO5bUVzk2mn_rYhXPRwvIDRF4.dVTN0UDLwMTN0czW}*

## Other users with su
**Commands used:**
- `su some-user`  : Used to switch user to the specified user name

**Thought Process:**
- Need to switch to the "zardus" user and then run `/challenge/run` to get the flag so we do that by using `su`.

**Solution:**
- Start the challenge, input the command `su zardus` and enter the correct password "dont-hack-me" to switch user to zardus to be able to run `/challenge/run` and get the flag.  

**Flag Obtained:**
> *pwn.college{k3LGVo5BlllWK25WnF3RbvBFLCT.dZTN0UDLwMTN0czW}*

## Cracking passwords
**Commands used:**
- `c`  : Used to

**Thought Process:**
- Need to

**Solution:**
- Start the challenge, input the command 

**Flag Obtained:**
> **

## Using sudo
**Commands used:**
- `c`  : Used to

**Thought Process:**
- Need to

**Solution:**
- Start the challenge, input the command 

**Flag Obtained:**
> **