# Open Messaging built using NodeJS

### To clone via the git CLI
#### Installing Git
Git download URL: https://git-scm.com/downloads

#### Clone to PC
**Instructions for Windows**
```
Open powershell.exe as administrator
cd Desktop
git clone https://github.com/m0thm4n/Open-Messaging.git
cd Open-Messaging
node app.js
```

### Configuring the .env file
###### The .env file needs to configured with your own settings
```
clientId = "" # OAuth client ID
clientSecret = "" # OAuth client secret
messageDeployment = "" # Your Open Messaging Integration ID
region = "" # The API region for your org
environment = "" # The region for your test org

THESE ARE ALL NOT CURRENTLY IMPLEMENTED
nickname = "" # The nickname you want to use
email = "" # The email you want to use
firstName = "" # The first name you want to use
lastName = "" # The last name you want to use
```

### Installing NodeJS

#### Download links
Current (v18 as of the writing of this README): https://nodejs.org/en/download/current/

LTS (v16 as of the writing of this README): https://nodejs.org/en/download/

##### Windows

###### NodeJS v18
Go to: https://nodejs.org/dist/v18.7.0/node-v18.7.0-x86.msi

###### NodeJS v16
Go to: https://nodejs.org/dist/v16.16.0/node-v16.16.0-x86.msi

##### Linux (Debian / Ubuntu)

###### NodeJS v18
```
# Using Ubuntu
curl -fsSL https://deb.nodesource.com/setup_18.x | sudo -E bash -
sudo apt-get install -y nodejs

# Using Debian, as root
curl -fsSL https://deb.nodesource.com/setup_18.x | bash -
apt-get install -y nodejs
```

###### NodeJS v16
```
# Using Ubuntu
curl -fsSL https://deb.nodesource.com/setup_16.x | sudo -E bash -
sudo apt-get install -y nodejs

# Using Debian, as root
curl -fsSL https://deb.nodesource.com/setup_16.x | bash -
apt-get install -y nodejs
```

##### MacOS

###### NodeJS v18
Go to: https://nodejs.org/dist/v18.7.0/node-v18.7.0.pkg

###### NodeJS v16
Go to: https://nodejs.org/dist/v16.16.0/node-v16.16.0.pkg

##### Ngrok for port forwarding

###### https://ngrok.com/

###### To run the app use the following command in the directory where you cloned the project

```node app.js```

### Troubleshooting

You will see undefined come up in the messages. This is unknown behavior and not expected working to determine the cause of this.
