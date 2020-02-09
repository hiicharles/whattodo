Ubuntu - Applications to Install
================================

## For General Use

* Brave Browser - [Website](https://brave.com/)

        # GPG key
        curl -s https://brave-browser-apt-release.s3.brave.com/brave-core.asc | sudo apt-key --keyring /etc/apt/trusted.gpg.d/brave-browser-release.gpg add -

        # Repository
        echo "deb [arch=amd64] https://brave-browser-apt-release.s3.brave.com/ stable main" | sudo tee /etc/apt/sources.list.d/brave-browser-release.list

        # Installation
        sudo apt update
        sudo apt install brave-browser        

        # Extensions
            - Ghostery - Privacy Ad Blocker
            - Ghostery Start Tab
            - Stands Fair AdBlocker
            - Poper Blocker
            - uBlock Origin


* Cliqz - [Website](https://cliqz.com/en/desktop/cliqz-for-linux)

        # GPG key
        sudo apt-key adv --keyserver hkp://keyserver.ubuntu.com:80 --recv-keys 4E0C443A

        # Repository
        echo deb http://repository.cliqz.com/dist/debian-release stable main | sudo tee /etc/apt/sources.list.d/cliqz.list

        # Installation
        sudo apt-get update
        sudo apt-get install cliqz


* Shutter - [Website](https://shutter-project.org/)

        # URL
        https://www.linuxuprising.com/2018/10/shutter-removed-from-ubuntu-1810-and.html

        # Repository
        sudo add-apt-repository ppa:linuxuprising/shutter

        # Installation
        sudo apt-get update
        sudo apt install shutter
        sudo apt install gnome-web-photo

        # Notes
        The new Shutter 0.94 from the repository does not have dependencies issue (for Edit).
            - libgoo-canvas-perl
            - libgoocanvas3
            - libgoocanvas-common issue.

* Skype - [Website](https://www.skype.com/en/get-skype/)

        # Notes
        The one on the website is newer than the one in the repository.

* VSCodium - [Website](https://vscodium.com/)

        # GPG key
        wget -qO - https://gitlab.com/paulcarroty/vscodium-deb-rpm-repo/raw/master/pub.gpg | sudo apt-key add -        
        
        # Repository
        echo 'deb https://gitlab.com/paulcarroty/vscodium-deb-rpm-repo/raw/repos/debs/ vscodium main' | sudo tee --append /etc/apt/sources.list.d/vscodium.list

        # Installation
        sudo apt update
        sudo apt install codium


## For Development

* DBBeaver Community - [Download](https://dbeaver.io/download/)

* Git - [Download](https://git-scm.com/download/linux)

        # Repository
        add-apt-repository ppa:git-core/ppa

        # Installation
        sudo apt update
        sudo apt install git

* pgAdmin 3 - [Download](https://www.pgadmin.org/download/)
* pgAdmin 4 - [Download](https://www.pgadmin.org/download/)
* Postman for Windows - [Download](https://www.getpostman.com/downloads/)
* Redhat OpenJDK 8 64bit - [Download](https://developers.redhat.com/products/openjdk/download)
* Redhat OpenJDK 11 64bit - [Download](https://developers.redhat.com/products/openjdk/download)
* STS 4 - [Download](https://spring.io/tools)




## For Work

* Forticlient VPN - [Download](https://www.forticlient.com/downloads)
* MobaXterm Home Edition - [Download](https://mobaxterm.mobatek.net/download-home-edition.html)


