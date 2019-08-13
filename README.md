# enph353_rosinstall

## Workspace setup steps

    cd src
    git clone git@github.com:GriffinPeirce/enph353_rosinstall.git
    cd enph353_rosinstall
    cp indigo.rosinstall ../.rosinstall
    cd ..
    rosws update
    cd ..
    catkin_make