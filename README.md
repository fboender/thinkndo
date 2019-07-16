Think'n'do
==========

A hierarchical outliner and todo manager.

![](https://raw.githubusercontent.com/fboender/thinkndo/master/screenshot.png)

## Installation

    sudo apt install python3-pyqt5
    git clone git@github.com:fboender/thinkndo.git
    cd thinkndo
    sudo cp -ar src /usr/local/lib/thinkndo
    sudo ln -s /usr/local/lib/thinkndo/thinkndo /usr/local/bin/thinkndo

## Keybindings

Thinkndo uses Vi-like keybindings:

### Movement

* `h`: Go to parent item
* `j`: Go to next item
* `k`: Go to previous item
* `l`: Go down the tree or add a new item under current item
* `/`: Search
* `n`: Jump to next search match
* `m[a-zA-Z]`: Set mark
* ``[a-zA-Z]`: Jump to mark

### Tree manipulation

* `a`: Edit item
* `d`: Delete item
* `o`: Insert item above
* `o`: Insert item below
* `p`: Paste (deleted) entry below
* `shift-p`: Paste (deleted) entry above
* `ctrl-shift-p`: Paste (deleted) entry as children of current item
* `shift-v`: Start visual mode. Grow the selection using `h`, `j`, `k`, `l`.
  You can then use `d` to delete the selection and `x` to mark them done.
* `c`: Toggle expanded item
* `shift+c`: Toggle auto-close of subtree
* `shift+j`: Move item down
* `shift+k`: Move item up
* `control+shift+j`: Move item down to next item with same checked status or
  icon.
* `control+shift+k`: Move item up to next item with same checked status or
  icon.

### Other

* `q`: Close program
* `x`: Toggle done
* `Escape`: Close program

## License

Released under the GPLv3. See the [LICENSE](LICENSE) file for more info.
