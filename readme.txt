--------------------------------------------------
             Installation
--------------------------------------------------

wget https://raw.githubusercontent.com/ninzahost/check-inodes-cpanel-user/main/check_inodes
chmod 755 check_inodes



--------------------------------------------------
             Usages 
--------------------------------------------------
./check_inodes


By short :- 

./check_inodes | sort | uniq -c | sort -n
