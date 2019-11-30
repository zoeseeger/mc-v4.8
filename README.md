## Installation

Make sure you do not have a midnight commander process running.

    mkdir -p ~/.config
    cd ~/.config
    git clone https://github.com/zoeseeger/mc-v4.8
    rm -r ~/.config/mc
    mv mc-v4.8 mc
    
    mkdir -p ~/.local/share/mc/skins
    cp ~/.config/mc/skins/*ini ~/.local/share/mc/skins/
