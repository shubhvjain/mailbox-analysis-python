To analyze emails inside a mbox file.

#### Adding user data
Create a python file named `data.py`. This will contain all user related data required to analyze the emails.

It must contain  - 
- `fileName` : name of the mbox file you want to analyze, must be in the same folder (all .mbox files are gitignored so they will not be commited)
- `myEmail` : your email id, to distingush between emails sent and recieved


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
