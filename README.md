## IMPORTANT!

#### First of all, for deployment you need to specify at secrets host, user and ssh key. You put private ssh key into secrets and its public key in authorized_keys in your server. This gives you permission to connect to your server.
##### Addition to first - if you have submodules - use ssh reversed. Add private key to your server, public - to github. Add ssh-agent activation & ssh-key adding in you profile so you will use that key every time user connects to your server.

#### Second, you create user using name you used in secrets and gave him permission to directory you will deploy. Advice - use groups.

#### Third, if you have any extra containers you want to connect to - connect them to network. Of course, you have to create network first.
