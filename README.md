A fork of rosnehook designed to kill other (rosne/cathook based) bots.


# Download and Install (anti) Rosnebots

    git clone https://github.com/gkursi/anti-rosnebot-setup; cd anti-rosnebot-setup; ./install-catbots; ./update; cd .
    
Next you will have to edit the text document called accounts.txt in your catbot-setup folder and put the bots accounts in this format:

USERNAME:PASSWORD

USERNAME:PASSWORD

USERNAME:PASSWORD

## Required Dependencies
Ubuntu/Debian
`sudo apt-get install nodejs firejail net-tools x11-xserver-utils`

Fedora/Centos
`sudo dnf install nodejs firejail net-tools xorg-x11-server-utils`

Arch/Manjaro/Garuda (High Support)
`sudo pacman -Syu nodejs npm firejail net-tools xorg-xhost xorg-server-xvfb`
