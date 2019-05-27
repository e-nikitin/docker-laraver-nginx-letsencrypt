**First run init-letsencrypt.sh**
``` bash
sudo ./init-letsencrypt.sh
```
**If run on local machine - need run this command**
```bash
sudo ./init-ssl.sh
```
**Add ssl-dhparams.pem to ./certbot/conf**

``` bash
sudo openssl dhparam -out ssl-dhparams.pem 2048
```