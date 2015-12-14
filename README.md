Monitoring pluging POSTFIX python

This plugin allows you to monitor your POSTFIX server.
Requirements

- New relic account, find our plugin in the plugin central
- Python 2.7 with the python lib requests installed ( pip install requests // find the library directly into the OS's official repository // build it from the sources : http://www.python-requests.org/)
- pflogsumm installed

- By now, it's required mails' log are located into /var/log/mail.log

Installation

Create the newrelic conf directory if it is not created yet
mkdir /etc/newrelic

Copy the config file into this directory
sudo cp nfs-agent-a0labs.cfg /etc/newrelic

Fill the informations in the cfg file:
- Licence Key
Optionnal:
- enable/disable logs and specify the directory

Now you are good to go, just launch the plugin and keep it running (daemon/nohup)

Support

Please use Github issues for support.