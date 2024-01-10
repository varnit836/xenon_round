Section A

2. Each linux command has an option --help which helps the end user to understand the use
cases via examples. Similarly if I execute internsctl --help it should provide me the
necessary help

Solution - To do this i have go to to root directory using below command
![image](https://github.com/varnit836/xenon_round/assets/53986191/94c1ed8e-71cc-4247-b2ab-4fb5ebcf82f0) 
Then i have used nano command to create custom command, to create internsctl command write 
nano internsctl and write below code
![image](https://github.com/varnit836/xenon_round/assets/53986191/6afc0eda-4f3e-40f9-a6cb-503983f8afda)
then to give permission write chmod +x internsctl

![image](https://github.com/varnit836/xenon_round/assets/53986191/13b4ae9c-8c37-44a8-9fbd-63d6aa0a7659)
now the custom commands is created.

Output:-

![image](https://github.com/varnit836/xenon_round/assets/53986191/74047881-0b7e-4c5b-a5ec-efbbd9d4642b)


3. I want to see version of my command by executing
internsctl --version

Solution- 
Custom command already created in step 2


Output-![image](https://github.com/varnit836/xenon_round/assets/53986191/43c9edd7-dbee-4ef0-9f08-9fdfb5d11071)


Section B
I want to execute the following command for -
Part1:-  Level Easy
I want to get cpu information of my server through the following command:
$ internsctl cpu getinfo

Solution:-

Inside root write nano internsctl cpu getinfo and write lscpu in it
![image](https://github.com/varnit836/xenon_round/assets/53986191/01b6c851-1ff6-4872-9bf8-7eaceef50eea)
then to give permission write chmod +x internsctl cpu getinfo

Output - 
![VirtualBox_Ubuntu_10_01_2024_16_25_53](https://github.com/varnit836/xenon_round/assets/53986191/d40866ee-687e-4450-abc8-d04d47145c94)



---
I want to get memory information of my server through the following command:
$ internsctl memory getinfo

Solution - 
Inside root write nano internsctl memory getinfo and write free in it
![image](https://github.com/varnit836/xenon_round/assets/53986191/0a47fd5f-585d-4fcc-aa6c-4218b8378b80)
then to give permission write chmod +x internsctl memory getinfo.

Output :-
![image](https://github.com/varnit836/xenon_round/assets/53986191/daa6ff70-703a-4230-9969-46a0cba32ba2)



Part2 | Level Intermediate
I want to create a new user on my server through the following command:

I want to list all the regular users present on my server through the following command:
$ internsctl user list
---

Solution- 

Inside root write nano internsctl user list and write below code in it
![image](https://github.com/varnit836/xenon_round/assets/53986191/cd57d39a-5c9d-4a47-bfe8-9b743337b8e1)

then to give permission write chmod +x internsctl user list.

Output :-

![image](https://github.com/varnit836/xenon_round/assets/53986191/a1d6554d-946e-4178-9100-00732c752397)

