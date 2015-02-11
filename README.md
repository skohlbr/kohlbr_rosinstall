kohlbr_rosinstall
=================

Repo for storing various (mostly testing related) rosinstall files 

Example quick dedicated  workspace setup:

mkdir -p atlas_planning/src
cd atlas_planning/src
wstool init .
wstool merge https://raw.githubusercontent.com/skohlbr/kohlbr_rosinstall/master/moveit_atlas.rosinstall
wstool update
