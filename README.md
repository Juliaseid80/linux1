   0 cd /home
   1 mkdir -p /home/animals/dogs
   2 touch animals/dogs/pluto.txt
   3 cd animals
   4 mkdir cats
   5 touch cats/garfield.txt
   6 mkdir fish
   7 touch fish/nemo.txt
   8 cd /home
   9 tree
  10 cd /tmp
  11 touch adam.txt
  12 cd /home
  13 mkdir humans
  14 cp /tmp/adam.txt home/humans
  15 tree
  16 cd /tmp
  17 touch evA.txt
  18 mv evA.txt /opt/eve.txt
  19 mv /opt/eve.txt /home/humans/
  20 cd /home
  21 tree 
  22 history > history.txt
  23 export_file history.txt
