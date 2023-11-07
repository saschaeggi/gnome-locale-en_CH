# Gnome en_CH locale

Sources : 
 - https://github.com/cbaconnier/ubuntu-locale-en_CH
 - https://lh.2xlibre.net/locale/en_US/
 - https://lh.2xlibre.net/locale/de_CH/

# Installation

_tested on Fedora 39_

	wget https://raw.githubusercontent.com/saschaeggi/gnome-locale-en_CH/master/en_CH
	sudo localedef -i en_CH -f UTF-8 en_CH.UTF-8 -c -v
	sudo mv en_CH /usr/share/i18n/locales/
	
	
 - Change the regional settings with the new locale in `Language Support` > `Regional Formats` and search for `Switzerland (English)`

Next time you log in, the locale should be in use.
