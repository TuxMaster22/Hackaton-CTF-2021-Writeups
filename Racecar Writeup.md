Ssh kick us out.

SCP did not work either

Why not sftp.

found out those files 

found out rc file


I downloaded with 

get rc kali@kali:~

![1](https://user-images.githubusercontent.com/78656150/133910233-49630a48-d27c-4673-a13c-80e7e44608f8.jpg)


pkill and then a logout, that’s  insane

I added a simple echo to the rc file.
![2](https://user-images.githubusercontent.com/78656150/133910238-2bb8a575-1300-4ed2-be96-d8a4afbb659d.jpg)


save it and then went back to the SFTP session.

![3](https://user-images.githubusercontent.com/78656150/133910240-51ec4bfb-f027-42ac-815e-423bd3a1bd67.jpg)

![4](https://user-images.githubusercontent.com/78656150/133910242-7b640a73-b356-4acf-86ad-c1350ede3357.jpg)


I uploaded the new rc file inside the old rc file.


finally!
![5](https://user-images.githubusercontent.com/78656150/133910253-8fbba43a-e007-49b0-9404-43f9b3c8a543.jpg)

what about checking privileges
![6](https://user-images.githubusercontent.com/78656150/133910255-b8cdaa42-e93f-469a-8fef-b27c34cb6ef3.jpg)


Awesome, as you may see just using sudo and find I found the flag.

thanks!

