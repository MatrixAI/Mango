This file documents the procedures that was undertaken to achieve Prototype-00. 

#Install Nginx

##Creating a server block
[Guide](https://www.digitalocean.com/community/tutorials/how-to-set-up-nginx-server-blocks-virtual-hosts-on-ubuntu-14-04-lts)

Created example.com on mango.mango:255 (also available on 180.200.128.124:255). 

To create mango.mango:255 go to terminal. Then:

1. sudo nano /etc/hosts
2. cat /etc/hosts
3. Add: 

180.200.128.124 mango.mango"

##Python Fibonacci Sequence 

def fibonacci(sequence_length_int):
    seed_old_int = 0
    seed_new_int = 1
    count_int = 1
    fibonacci_list = [0, 1,]
    while count_int <= int(sequence_length_int):
        fibonacci_int = seed_old_int + seed_new_int
        fibonacci_list.append(fibonacci_int)
        seed_old_int = seed_new_int
        seed_new_int = fibonacci_int
        count_int += 1
    return(fibonacci_list)

sequence_length_int = input("Define your desired sequence length: ")
print()

fibonacci_list = fibonacci(sequence_length_int)

print("Fibonacci sequence with length {} is {}".format(sequence_length_int,fibonacci_list))
