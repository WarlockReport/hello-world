http://www.karakaram.com/git-install

https://help.github.com/articles/using-ssh-over-the-https-port/

To set this in your ssh config, edit the file at ~/.ssh/config, and add this section:

Host github.com
  Hostname ssh.github.com
  Port 443

The authenticity of host 'github.com (207.97.227.239)' can't be established.
RSA key fingerprint is xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
Are you sure you want to continue connecting (yes/no)? yes

edit on web

edit at local