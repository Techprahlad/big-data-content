# Installation
- To install the sqoop 1.4.4 we followed the given sequence of steps :

- Download the sqoop-1.4.4.bin_hadoop-1.0.0.tar.gz file from www.apache.org/dyn/closer.cgl/sqoop/1.4.4
- Unzip the tar file: sudo tar -zxvf sqoop-1.4.4.bin hadoop1.0.0.tar.gz
- Move sqoop-1.4.4.bin hadoop1.0.0 to sqoop using command

`user@ubuntu:~$ sudo mv sqoop 1.4.4.bin hadoop1.0.0 /usr/lib/sqoop`

- Create a directory sqoop in usr/lib using command

`user@ubuntu:~$ sudo mkdir /usr/lib/sqoop`

Go to the zipped folder sqoop-1.4.4.bin_hadoop-1.0.0 and run the command

`user@ubuntu:~sudo mv ./* /usr/lib/sqoop`

Go to root directory using cd command

```
user@ubuntu:~$ cd
Open .bashrc file using

user@ubuntu:~$ sudo gedit ~/.bashrc
Add the following lines

export SQOOP_HOME=¡usr/lib/sqoop
export PATH=$PATH:$SQOOP_HOME/bin

```


- To check if the sqoop has been installed successfully type the command

- sqoop version
