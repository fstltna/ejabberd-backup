# eJabberd backup script (1.0.0)
Creates a backup of your eJabberd installation and MySQL data

Official support sites: [Official Github Repo](https://github.com/fstltna/ejabberd-backup)

---

1. Edit the settings at the top of ejabberdbackup.pl if needed
2. create a cron job like this:

        1 1 * * * /root/ejabberd-backup/ejabberdbackup.pl

3. This will back up your eJabberd installation at 1:01am each day, and keep the last 5 backups.

4. Edit the backup config:
	Run a manual backup and it will ask you for the mysql config info. If you need to reconfigure it use the "-prefs" command-line option

If you need more help visit https://xmpp-jabber.retro-os.live/
