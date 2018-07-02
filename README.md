# first-react-pwa
This repository gives a overview how we can implement progressive web app in react js.


## Steps For Running This Application
Make sure you have latest version of node at least Node v6.

### Step 1:
Open the terminal and run this command 

`$git clone https://github.com/PulkitAgg/first-react-pwa.git`

#### Step 2:
Migrate to the project which is cloned right now i.e run this commmand 

` cd first-react-pwa`

### Step 3 : 
Install the required packages using this command 

`$npm install`

### Step 4:
Now you are ready with project just hit this command on command line 

`$npm start`

This command will open the `http://localhost:3000/` in the default browser. You can audit this application against the Progressive Web App. It will pass all the audits except one i.e  'Does not redirect HTTP traffic to HTTPS'. This will be removed when you host your application.
For Auditing you have to open the developer tool and go the audit section and select the Progressive Web App and click on Run Audit.

### Step 5:
Go to the developer tools and select the Application. In application click on manifest file and click on `Add to homescreen` link.
This will add this application to your home screen.

If you want to add this application to your android or ios mobile phone.
Check your network ip using `ipconfig` (for windows) `ifconfig` (for linux or mac). And open you mobile browser with `${YOUR_IP_ADDRESS}:3000`. Please confirm that your laptop and mobile must be connected on the same network. Now you can add this application to your mobile home screen by taping on add to home screen.

OR you have to host this application to the server and run in the mobile browser.
