# Basics..
- consol vs shell vs terminal:
    - terminal--> A program that provides a user interface to interact with a computer system through text-based input and output.
    - shell --> A command interpreter program that enables users to interact with an operating system, executing commands and scripts, example: zsh.
          - You can know your default shell:
                      - echo $SHELL .
          - You can know all shell types :
                      - ls /bin/*sh .
    - consol --> The interface where users can input commands and execute them to perform specific tasks or operations, python interpreter .
 
- Usefull commands :
  - source --> command is used to execute the content of a script within the current shell environment, ex:source /path/to/myscript.sh  .
  - whoami -->  is used to print the username of the current user .
  - ifconfig (linux)--> print public ip address .
  - ipconfig getifaddr en0 (mac) --> print public ip address .
  - 
       
# Piping..
- What is shell piping? 
![WhatsApp Image 2024-02-02 at 19 59 52](https://github.com/SamerEH213/My_learning/assets/125601349/a752d0b1-49ec-439c-987d-303be154685c)

- In terminal:
![WhatsApp Image 2024-02-02 at 19 59 58](https://github.com/SamerEH213/My_learning/assets/125601349/8a60aaec-ad35-4092-8e8d-fb4e311d68b7)


# SSH..
- What is SSH? protocol is a method for securely sending commands to a computer over an unsecured network. SSH uses cryptography to authenticate and encrypt connections between devices.
![422460911_1049714876122015_8757367640748001328_n](https://github.com/SamerEH213/My_learning/assets/125601349/11ead7de-3ff4-4c3f-a1bd-3fd43d36a18e)

- SSH standard for Secure Shell .
- for conecct with your server :
       1)First --> Creating SSH keys using ssh-keygen .
             -  The location for the keys that will be generated. By default, the keys will be stored in the ~/.ssh directory within your user’s home directory. The private key will be called id_rsa and the associated public key will be called id_rsa.pub.
       2)Second --> Copying the public key into your server using .ssh/authorized_keys .
       3)Third -->  connect with your server using ssh username@remote_host.
                     - username for server ( can find username throgh whoami ).
                     - remote_host --> public IP address for your sever .
                     - ssh -N -L 8080:127.0.0.1:8080 username@ip  ( if you need connect with specific port in server and local machine ) .


# Bash scripting..
- What is Bash scripting? Bash scripting (linux,mac) is a file containing a sequence of commands that are executed by the bash program line by line .
- Bash standard for Bourne Again SHell .
- Bash scripting is not a programming language .
- 






















   
     


 
