#!/bin/bash
#Purpose: Backup jenkins home directory
#AUthur: Tobenna Okoli
#Version: 1.0
SRC=/var/lib/jenkins
DST=/home/ubuntu/backups
DATE=`date +%F`

[ -e $DST ] || mkdir $DST

tar -cvzf $DST/jenkins-$DATE.tar.gz $SRC
