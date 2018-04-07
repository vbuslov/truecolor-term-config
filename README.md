# Truecolor terminal config

This is files neede to run Emacs in true color mode in terminal:

    git clone git@github.com:vbuslov/truecolor-term-config.git ~/truecolor-term-config

    cd ~/truecolor-term-config
    tic -x -o ~/.terminfo terminfo-24bit.src

Test:

    cd ~/truecolor-term-config
    ./truecolor.sh
