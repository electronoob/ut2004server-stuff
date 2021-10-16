# ut2004server-stuff
ut.iomods.com


This contains server source code that i found freely online, but it's obviously not -free-, i personally own a copy of the game and i guess you need to as well to use this ? who knows, in fact, who cares.


start server with
from System dir on linux


  9  sudo apt install unzip
   10  unzip DedicatedServer3339-BonusPack\[ut2004-lnxpatch3369-2\].zip
   11  sudo dpkg --add-architecture i386
   12  sudo apt update
   13  sudo apt-get install libstdc++5:i386
   14  cd DedicatedServer3339-BonusPack\[ut2004-lnxpatch3369-2\]/
   15  ls
   16  cd System/
   17  vim UT2004.ini
   18  clear
   19  ls
   20  chmod +x ucc-bin

  ./ucc-bin server DM-Monstertrap?game=SkaarjPack.Invasion?Mutator=XGame.MutQuadJump,XGame.MutRegen,XGame.MutZoomInstagib ini=target-practice.ini -nohomedir
