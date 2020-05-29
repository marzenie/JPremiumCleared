![Theme](https://raw.githubusercontent.com/Jakubson/JPremium/master/images/916fd6ff9b545ba89a7f395da3d113e34b1c6233.png)

## Introduce
JPremium is an authorization BungeeCord plugin. JPremium is different from other popular authorization plugins. The plugin has a very necessary feature, which many servers need, automatically login premium players. The plugin works based on a limbo server structure. That means you have to have a separate Spigot server which is the limbo server. On the below image, you can see the limbo server is an authorization server, where players login or register. 

## Features
* JPremium logins automatically premium players. They also can disable that feature and login with a password. Automatic registration is dependent on your JPremium configuration. You can set automatic registration premium players, but then cracked players with premium nicknames cannot join to the server.
* JPremium has fully supported changing premium nicknames. Premium players who change their nickname will not lose any data and will not be able to steal any cracked accounts. Please remember that feature works only when you have enabled `fixedUniqueIds` in your JPremium configuration. If you have not enabled that option, premium players will not be able to join the server after changing their nickname.
* JPremium has sessions for cracked players. When cracked players have a session, they do not have to login every joining. You can set automatic starting sessions for specified time after registration and login.
* JPremium has protection against bots. The first protection is forbidding joining if JPremium detects too many joining requests. Even if bots join the server, bots cannot register because JPremium requires entering captcha codes from maps. You can change the icon on the captcha maps.
* JPremium connects all not logged players with the limbo server. They have to login or register there and then they will be connected with the main server or their last server on which they were before quitting from the server. When one of the servers is shut down, all players from that server will be redirected to the limbo server. And when that server comebacks, all redirected players will be connected to that server again.
* JPremium forbids joining directly with Spigot servers without your BungeeCord server. The plugin uses access tokens to validate connections. It is a very good means of protection, but please remember that any plugins do not warrant full protection, I recommend having a firewall!
* JPremium uses salted SHA-256 to hash cracked player passwords. The plugin alos requires entering strong passwords by cracked players.

## Requirements
* JPremium requires the following stuff to work: BungeeCord server, at least two Spigot servers, MySQL database and the Internet connection.

## Images

![Network Structure](https://raw.githubusercontent.com/Jakubson/JPremiumCleared/master/images/NetworkStructure.png)
![](https://raw.githubusercontent.com/Jakubson/JPremiumCleared/master/images/image1.png)
![](https://raw.githubusercontent.com/Jakubson/JPremiumCleared/master/images/image2.png)
![](https://raw.githubusercontent.com/Jakubson/JPremiumCleared/master/images/image3.png)
![](https://raw.githubusercontent.com/Jakubson/JPremiumCleared/master/images/image4.png)
![](https://raw.githubusercontent.com/Jakubson/JPremiumCleared/master/images/image5.png)
![](https://raw.githubusercontent.com/Jakubson/JPremiumCleared/master/images/image6.png)
![](https://raw.githubusercontent.com/Jakubson/JPremiumCleared/master/images/image7.png)
![](https://raw.githubusercontent.com/Jakubson/JPremiumCleared/master/images/image8.png)
