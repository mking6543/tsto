The Simpsons Tapped Out tool
====

Installation (or if you're Windows user see release section to download latest executable):
- install Python;
- install Google protobuf library for Python (using pip for example);
- install Requests Python library (using pip for example).

Usage examples

List of supported commands:

    python tsto.py
    help
    quit

Store your town status into ./land.backup file:

    python tsto.py
    login email@host.com password
    download
    save land.backup
    quit

Add 100 squidport tiles (5000), 999 golden scratchers (44), 999 buddha (9):

    python tsto.py
    login email@host.com password
    download
    ia 5000 2 100
    ia 44 2 999
    ia 9 2 999
    upload
    quit

Add 9999999 KrustyLand tickets (11, see spendablemasterlist.xml):

    python tsto.py
    login email@host.com password
    download
    spendable 11 9999999
    upload
    quit

Set current level and FP level to given values:

    python tsto.py
    login email@host.com password
    download
    setlevel 58
    vs SocialLevel 20
    upload
    quit

Add 1000 donuts to your account email@host.com:

    python tsto.py
    login email@host.com password
    download
    donuts 1000
    upload
    quit

The script has a lot of things to do; just execute 'help' command and examine it output.

DONATE

If you want to help this project please send your PayPal donations to jsbot@ya.ru
Thank you.
