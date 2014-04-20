Legends of iQuestria Login Server
===================================

iQuestria LoE Login server, original project from GitHub user tux3. You can see the original repo <a href="https://github.com/tux3/LoE-PrivateServer">here</a>.

Hey everyone! You like Legends of Equestria, don't you? Isn't it sad that the servers are down most of the time? Well now you can play with your fellow iQuestrians on our official server! Now, this server isn't like the official ones since they haven't released a real server. This had to be done from scratch, built in C++. Basically what I'm trying to say is there isn't as much features as the official servers.

<a href="http://datastorage.iquestria.net/loe/login/release/Legends%20of%20iQuestria%20Login%20Server.zip">Download current version from iQuestria Servers</a>

(sorry, I can't upload the pre-patched LoE, copyright...)
​
## Downsides:
- Almost no monsters, and none of them can fight.
- Not as many quests as the official servers.
- No "natural" items to collect (flowers, gems, ...)

## Upsides:
- Up 24/7-ish!
- Unlimited slots!
- Good admins & mods
- It's iQuestria!

#Login Server Setup (the hard part)

##Step 1. Patch LoE
To bypass LoE's login system, we have created our own which also allows you to access the server. Firstly, download the zip file here and extract it. Then take the loe_Data and put it into your Legends of Equestria folder as shown here. Don't worry, it will ask to replace some files, this is normal. But, <b>MAKE SURE LEGENDS OF EQUESTRIA IS CLOSED.</b>
<img src="http://i.gyazo.com/89034c39f336f5bc1a9ac39b0ef86e93_1.png"></img>

##Step 2. Set up the login server
Now, open up that Legends_Of_iQuestria-LoginServer.exe (long name I know) and you might a Windows Firewall warning. Click "Allow access" on this.
<img src="http://i.gyazo.com/2942b420100a01aad0b5a5f32da77be0_1.png"></img>

##Step 3. It's started!
If you see the "Server started" in the log, you're all set! (Don't mind any errors such as "Error reading players database", it will create the database automatically)
<img src="http://i.gyazo.com/bb6885c07fc878428c7d2e73415b52da.png"></img>

##Step 4. Join the server
Open LoE, sign in with whatever the heck you want and you should see all of the official servers replaced with the iQuestria server. (I would add the official ones but they're not compatible with the server we're running)
<img src="http://i.gyazo.com/87b5fdfcf9877fa76217d0afe5ab4368_1.png"></img>
<img src="http://i.gyazo.com/a17684b30457023c516f408ee93d015c.png"></img>

#Developers
Want to help the project along? Know how to code in C++/Qt? Come contribute to our fork of the server on GitHub at iQuestria/LoE-PrivateServer (you're already here!). We accept pull requests if they're helpful!

project based off of tux3/LoE-PrivateServer at github
