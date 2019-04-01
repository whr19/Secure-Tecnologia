# Wpad Unofficial packages for pfSense software

As many people knows, Netgate has trimed a lot of packages from official repo since pfSense® 2.3. 

This repo updates some packages for newer pfSense software versions with manual procedure installs.

This is not supported by Netgate or pfSense team. Use it at your own risk.

Feedbacks and contributions are always welcome.

The wpad package confgigures antoher nginx http instance to host wpad file and proxy/squidguard error page as well. This way you can keep you firewall GUI under HTTPS.

# Install instructions

If you enabled the Unofficial repo, you can add this package under System -> Package Manager

Or add it under console/ssh.

cd /root

fetch https://raw.githubusercontent.com/whr19/Secure-Tecnologia/master/pkg-wpad/files/install_wpad_24.sh

sh ./install_wpad_24.sh

Once it finishes, all must be in place. If you do not see the menu after it finishes, try to install any pfSense package from GUI, like cron for example.
