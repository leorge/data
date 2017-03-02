# data
Clone this project,
and add the path to $HOME/.profile as below in your appropriate directory.  

    $ git clone https://github.com/leorge/data.git
    $ echo $PATH          # confirm
    $ cp ~/.profile .     # back up
    $ echo "PATH=\$PATH:`pwd`/data" >> ~/.profile

Login again.

    $ echo $PATH
    $ random.awk 22 | xargs echo
