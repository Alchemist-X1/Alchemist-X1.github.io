## Alchemist-x1 

This website was created by github pages and wiil be used to keep track of any experiences when learing bioinformatics.

### About github 

    You can create a account and github page by following the guide.

### About docker
1. Install docker
	  
	  The docker desktop could download from [docker hub](https://hub.docker.com/)
	
	  But there were something wrong because the installer didn't ask me to enable the Hyper-V, so when I tried to run hello-world to test if the docker could work, the power shell told me I can't run hello-world because lack of a feature.
	
	  I checked the Hyper-V option in 开启或关闭windows功能, the option had been selected already. But when checked the 控制面板, the vitural machine was forbade.
      
	  To solve this problem, need  to enter into BIOS and enable the Hyper-V, then the hello-world could be run which means the docker was installed.

2. load the learning document
   
   After the docker could work, I tried to load the GZ download from website.
   
   And then came the error:
   ![problem.png](https://i.loli.net/2019/09/15/7obKLeYMONE8Ixc.png)
   
   I tried if  the docker could regular load the GZ after I installing a linux, but even failed to find docker:
   ![try.png](https://i.loli.net/2019/09/15/NldiVL3faOjmw92.png)
   
   Seems like I need to switch the model to linux.
   
   However, the docker told me the memory was not enough when tried to switch.

