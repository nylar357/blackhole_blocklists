
adlist/blocklists you can add these lists to really any kind of adblocker whether its a browser extension or basically any kind of good adblock that can use lists.


# There's 4 lists here:

# StevenBlack List
    Pi-Hole list:
    Title: StevenBlack/hosts
    Number of unique domains: 184,034

Fetch the latest version of this file: https://raw.githubusercontent.com/StevenBlack/hosts/master/hosts
Project home page: https://github.com/StevenBlack/hosts
Project releases: https://github.com/StevenBlack/hosts/releases

# EasyList
    Domains on List : 4640
    Non-Domains : 28,000

EasyList is the primary filter list that removes most adverts from international webpages, including unwanted frames, images and objects. It is the most popular list used by many ad blockers and forms the basis of over a dozen combination and supplementary filter lists.

# EasyPrivacy
    
    Domains : 45
    Non-Domains : 20,080

EasyPrivacy is an optional supplementary filter list that completely removes all forms of tracking from the internet, including web bugs, tracking scripts and information collectors, thereby protecting your personal data.

# Fanboy's Social Blocking List
    
    Domains : 2235
    Non-Domains : 915

Fanboy's Social Blocking List solely removes Social Media content on web pages such as the Facebook like button and other widgets.

Grab those last 3 here :     
    https://easylist.to/

# For installing the Pi-Hole software :

One-Step Automated Install

Those who want to get started quickly and conveniently may install Pi-hole using the following command:

    curl -sSL https://install.pi-hole.net | bash
    
Alternative Install Methods

Piping to bash is controversial, as it prevents you from reading code that is about to run on your system. Therefore, we provide these alternative installation methods which allow code review before installation:
Method 1: Clone our repository and run

    git clone --depth 1 https://github.com/pi-hole/pi-hole.git Pi-hole
    cd "Pi-hole/automated install/"
    sudo bash basic-install.sh

Method 2: Manually download the installer and run

    wget -O basic-install.sh https://install.pi-hole.net
    sudo bash basic-install.sh

# I've also added the Pi-Hole tarball in the files.

![preview](pics/pihole1.png)

![preview](pics/pihole2.png)

![preview](pics/pihole4.png)
