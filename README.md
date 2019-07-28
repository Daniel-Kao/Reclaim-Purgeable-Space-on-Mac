# Reclaim-Purgeable-Space-on-Mac
1. open terminal 
2. mkdir ~/largefiles 
3. dd if=/dev/random of=~/largefiles/largefile bs=15m
4. cp ~/largefiles/largefile ~/largefiles/largefile2
5. repeat step 4 but with a different file name, largefile3, for example
6. wait for 5 mins, control + C 
7. see message 'disk critically low'
8. rm -rf ~/largefiles/ 