# hugo-gh-actions-server
A Github Action to deploy a hugo website to a server via SSH. 


I did not find any GH Action script to deploy my hugo page to my own server, so here it is. 

The SSH Action needs parameter to work which should not just be saved in the repo but as [secrets](https://docs.github.com/en/actions/reference/encrypted-secrets). It allows for more parameter than I used. More about that in its [documentation](https://github.com/easingthemes/ssh-deploy).




## Actions Used

https://github.com/actions/setup-node  
https://github.com/peaceiris/actions-hugo  
https://github.com/actions/cache  
https://github.com/easingthemes/ssh-deploy  
