# Birthday_Bot
This discord bot notifies all users when it is someones birthday.Also get there age and birthday that they gave the bot.

# Commands:
`.mybirthday Month,day,year` - you must do this to put you birthday before anything. arguments example `March 2, 1998`<br /> <br />
`.age @user` - this gives all the mentioned users age: Example: `.age @snow @user2 @user3` for multiple user's age <br /> <br />
`.myage` - to get your own age <br /> <br />
`.author birth` - to get my birthday <br /> <br />
`.author age` - to get my age <br /> <br />
`.birthday @user` - to get some users birthday <br /> <br />

# Invite bot to a server
https://discordapp.com/api/oauth2/authorize?client_id=596012231637073921&permissions=8&scope=bot

# using this code

## Install before running

```
pip3 install discord.py
```

### clone <br />
```
git clone https://github.com/moulid15/Birthday_Bot.git
``` 

### set up your token on linux  <br />
`` cd ``to go home <br /> <br />
```
vi .bashrc
```

In the .bashrc file replace `{token from discord}` with your token <br /> <br />

```
export token='{token from discord}
```
press `i` to enter vim, then add the the above script.

### set up your token on macOS  <br />
`` cd ``to go home <br /> <br />
```
vi .bash_profile
```

In the .bashrc file put replace `{token from discord}` with your token <br /> <br />

```
export token='{token from discord}
```
press `i` to enter vim, then add the the above script

```
python3 servertest.py
```
This will run the bot
