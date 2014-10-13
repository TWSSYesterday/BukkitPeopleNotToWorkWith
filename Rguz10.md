Setting up dedis for KevinEssence:
 * didn't set up pubkey auth
 * didn't lock root account
 * didn't set up sudo
 * innactive for 3 months
 * [2:29:33 AM] KevinEssence: I don't want to talk shit because he might ddos us.
 * wrote this backup script:```bash
echo "Backing up in"
sleep 1
echo "5"
sleep 1
echo "4"
sleep 1
echo "3"
sleep 1
echo "2"
sleep 1
echo "1"
zip -r "backup-$(date +"%d-%m-%Y").zip" /home/username/Factions
echo "Backing up externally in"
sleep 1
echo "5"
sleep 1
echo "4"
sleep 1
echo "3"
sleep 1
echo "2"
sleep 1
echo "1"
mv /home/username/"backup-$(date +"%d-%m-%Y").zip" /home/username/Backup_3
```
