Here is a little script which is monitoring the disk usage of your partitions.
The script can send you an e-mail if the usage is over 90%.

Just put it into your crontab and let it run hourly:

   0 * * * * /path/to/disk-usage.sh

Of course you need to change the $ADMIN to your adress and you are also able 
to change the percentage of usage which will be alerting.
