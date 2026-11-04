# PickThisSongForMe
(personal stuff but i like keeping it public)

#SHARED PARTITION
#delete dirs 
sudo mkdir -p /shared
blkid /dev/nvme0n1p3  #find UUID
sudo micro /etc/fstab
#add:  UUID=c62012f2-009e-431f-9198-dbb0b16cdcf0  /shared  ext4  defaults  0  2
sudo systemctl daemon-reload
sudo mount -a    #either the above one works or this one
findmnt /shared
sudo chown -R im4n:im4n /shared   #if permission issue

Sj$j4nk&wsUZvURE!r1M5FRq6VQ#5Txk8BUd&aq4
