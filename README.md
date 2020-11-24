# backup-cli

backup-cli is a bash shell based script intended to be a one-stop solution for all backup related tasks. 

## Jira

Use the backup-cli to take Jira backup following the recommended methods by [Atlassian](https://confluence.atlassian.com/adminjiraserver/backing-up-data-938847673.html)

### Usage
#### Local Backup
```bash
./backup-cli jira local
```
#### Azure Backup
```bash
./backup-cli jira azure
```

## Confluence

Use the backup-cli to take Confluence backup following the recommended methods by [Atlassian](https://confluence.atlassian.com/doc/production-backup-strategy-38797389.html)

### Usage
#### Local Backup
```bash
./backup-cli confluence local
```
#### Azure Backup
```bash
./backup-cli confluence azure
```
## Gitlab

Use the backup-cli to take Gitlab backup following the recommended methods by [Gitlab](https://docs.gitlab.com/ee/raketasks/backup_restore.html)

### Usage
#### Local Backup
```bash
./backup-cli gitlab local
```
#### Azure Backup
```bash
./backup-cli gitlab azure
```

## MongoDB

Use the backup-cli to take MongoDB backup using [mongodump](https://docs.mongodb.com/database-tools/mongodump/) command

### Usage
#### Local Backup
```bash
./backup-cli mongodb local --sslAllowInvalidCertificates --gzip --quiet
```
#### Azure Backup
```bash
./backup-cli mongodb azure --sslAllowInvalidCertificates --gzip --quiet
```
_Note: all the options of [mongodump](https://docs.mongodb.com/database-tools/mongodump/) command can be added at the end of the `./backup-cli mongodb` command in order to get the desired results._

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.



## License
[MIT](https://choosealicense.com/licenses/mit/)