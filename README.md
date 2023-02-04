# Kali-Signatures-Fix

gpg --keyserver keyserver.ubuntu.com --recv-key 7D8D0BF6

gpg -a --export 7D8D0BF6 | apt-key add -

apt update

done!
