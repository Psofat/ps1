# ps1
#ssh script

#!/bin/bash
USR="ps936d"
HOST="p3edd2m1.vci.att.com"

SCRIPT="pwd; ls"
echo "testing ssh"
pwd
echo "current location"

ssh -l $USR $HOST $SCRIPT

pwd
