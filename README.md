# satis.dutchento.org
Satis repository for private composer packages

set documentroot to `<project root>/repository`

run build.sh on the server. This will build the repository directory with the latest package versions

## Cronjob
Run build every 30 minutes
```
MAILTO=info@example.com
*/30 * * * * bash /path/to/build.sh > /dev/null 2>&1
```
