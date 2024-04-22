### Usage: john [OPTIONS] [PASSWORD-FILES]

John the Ripper is one of the oldest and most widely used password cracking tools in the cybersecurity community. 

It has a long history of development and has evolved over time to become a powerful and versatile tool for assessing password security.

 It's a password-cracking tool that can be used to test the strength of passwords by attempting to crack them using various techniques, including brute force.

### Installed Required - john

        sudo apt install john

### create password list using any tools

        crunch <min> <max> [options]
### Example

        crunch 6 8 -t @@@@@@% -o wordlist.txt


### 

        john --format=FORMAT --wordlist=WORDLIST router_hash.txt
    
you can also use rockyou.txt

###  see result \

        john --show router_hash.txt

