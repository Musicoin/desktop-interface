![Travis](https://img.shields.io/travis/etaletai13/interface.svg?style=for-the-badge)
![GitHub release](https://img.shields.io/github/release/etaletai13/interface.svg?style=for-the-badge)

# desktop-interface
Default UX Module for [Musicoin Desktop Client](https://github.com/Musicoin/desktop)

## Using
First, clone the main desktop codebase 
'git clone git@github.com/Musicoin/desktop.git'

Then, in the same directory containing 'desktop', clone this reposistory 
'git clone git@github.com:movingelectrons/desktop-interface.git'

Remove the line regarding 'interface' under 'dependicies' in 'package.json'

Then you can finally
'''
cd desktop && yarn add ../desktop-interface && yarn debug
'''

At this point the desktop client should popup and run.  From here on out you should be able to run 'yarn debug' to see the desktop client in action.

## Screenshot 
**Note**: *may be slightly out of date*
![http://srandd.com/mc_desktop_snap.png](http://srandd.com/mc_desktop_snap.png)
