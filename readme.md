To analyze emails inside a mbox file.

#### Adding user data
Create a python file named `data.py`. This is contain all user related data required to analyze the emails.

It must contain  - 

```
fileName="something.mbox" # name of the mbox file you want to analyze, must be in the same folder (all .mbox files are gitignored so they will not be commited)
myEmail = "youemail" (to distingush between emails sent and recieved)
```


#### To show 
- emails sent
	- total 
	- heatmap of time 
	- unique senders
	- word cloud
- emails recieved
	- total  
	- heatmap of time
	- unique recievers
	- word cloud  
