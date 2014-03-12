railo-ec2
=========

A user-data boot script install Railo 4, ready to run.

# This boot script will install Railo 4.0.4 in a server configuration on an Amazon
# EC2 Amazon Linux instance. To use this script, start your preferred method of 
# launching a new Amazon Linux instance. Make sure to add this line to the 
# "User Data" section of your command or launch screen.
#
#      #include
#      https://raw.github.com/muellermh/railo-ec2/master/boot_to_railo.sh
# 
# You could also copy the script to your own repo or instance available path.
# The new instance will book and install Tomcat and Railo, ready to run. Just drop your 
# code in /usr/share/tomcat7/webapps/ROOT or drop a WAR file in webapps. 
#
# Git is also installed, so you can add your own script on a new line in the "#Include"
# block to pull code, or do anything else you'd like.
#
# Be sure to check this repos wiki for more information and changes as they come in.
#
# '@Amaroom'
