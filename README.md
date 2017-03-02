# data
Clone this project, and add the path to $HOME/.profile as below.  

    $ git clone https://github.com/leorge/data.git
    $ echo $PATH                       # confirm
    $ cp ~/.profile ~/.profile.bak     # back up
    $ echo "PATH=\$PATH:`pwd`" >> .profile

Login again.

    $ random.awk 22 | xargs echo
