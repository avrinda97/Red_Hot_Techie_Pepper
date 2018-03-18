#Welcome to I-BOT
##An Intelligent Bot built with Python on ZulipChat

##Team: Red Hot Techie Pepper - Hack in the North 2018
                              
##Intriduction

This Bot deals with with various features required by a personal relocation assistant that brings superior service and unpralleled delight to the user.
While you relocate,I(BOT) give you advice on where to go,which direction to take,what to do etc.

##Features

1.Currency Convertor
2.Near by ATM's locator
3.Language Translator
4.Nearby Restaurants locator
5.Gides you direction to different places
6.Gives nearest bus transportation service
7.Helps you in finding your desired job in a particular location
8.Tourist Spots in the city
9.NLP Based instatnt response
10.AutoCorrects the queries and replies accordingly



## Instructions to run locally:
1. [Create a Zulip Realm](https://zulip.com/create_realm/)
2. Goto to settings and create a new generic bot named 'ibot'. (Settings can be found in dropdown of gear icon present in top right corner of zulip realm)
3. Download the zuliprc file for your bot and place it in your home directory as '.zuliprc'.
4. Install all the requirements using ``` pip install -r requirements.txt ```
5. In ``` bot.py ``` , change site in ``` self.client = zulip.Client(site="https://rhtp.zulipchat.com/api/") ``` to url of your created zulip realm.Do the same for ``` BOT_MAIL ``` variable.  
6. Run ``` bot.py ``` using python 3. ``` python3 bot.py ```
7. Head over to your created zulip realm and start using the bot.
 

## Contributors
* [Gunjan Singh](https://github.com/gunjansingh97)  
* [Naguboyina Sravya](https://github.com/sravya31)  
* [Prankur Agarwal](https://github.com/prankuragarwal)  
* [Vrinda Agarwal](https://github.com/avrinda97)    


##Contribute

Feel free to report issues and bugs.It will be helpful for future launches of application.
All Suggestions are welcome.
Fork repository and Contribute.

##Acknowlwdgements
Thanks to Zulip for providing Zulip Api and Platform.
