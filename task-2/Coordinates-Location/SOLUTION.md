~$ mkdir Coordinates-Location<br/>
~$ mkdir North<br/>
~$ cd North<br/>
~/North$ gedit NDegree.txt<br/>
~/North$ gedit NMinutes.txt<br/>
~/North$ gedit NSeconds.txt<br/>
~/North$ gedit NorthCoordinate.txt<br/>
~/North$ cp NorthCoordinate.txt /home/z0d/Coordinates-Location<br/>
~/North$ cd <br/>
~$ cd Coordinates-Location<br/>
~/Coordinates-Location$ mv NorthCoordinate.txt North.txt<br/>
~/Coordinates-Location$ mkdir East<br/>
~/Coordinates-Location$ cd East<br/>
~/Coordinates-Location/East$ gedit EDegree.txt<br/>
~/Coordinates-Location/East$ gedit EMinutes.txt<br/>
~/Coordinates-Location/East$ gedit ESeconds.txt<br/>
~/Coordinates-Location/East$ gedit EastCoordinate.txt<br/>
~/Coordinates-Location/East$ cp EastCoordinate.txt /home/z0d/Coordinates-Location<br/>
~/Coordinates-Location/East$ cd ~<br/>
~$ cd Coordinates-Location<br/>
~/Coordinates-Location$ mv EastCoordinate.txt East.txt<br/>
~/Coordinates-Location$ mv /home/z0d/North /home/z0d/Coordinates-Location<br/>
~/Coordinates-Location$ gedit Location-Coordinate.txt<br/>

~/Coordinates-Location$ cd<br/>
~$ git clone https://github.com/janvi213/amfoss-tasks<br/>
~$ cd amfoss-tasks<br/>
~/amfoss-tasks$ git add .<br/>
~/amfoss-tasks$ git commit -m "added"<br/>
~/amfoss-tasks$ git push<br/>
