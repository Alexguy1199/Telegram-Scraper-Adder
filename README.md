# Telegram-Scraper-Adder
A python script for scrapping members from another Telegram group and adding them to your group

Instruction for installation and operation:

<> Step 1: update linux

apt update && apt upgrade

<> Step 2:  install python3 and git

apt install python git

<> Step 3:  install Telegram-Scraper-Adder

git clone https://github.com/Alexguy1199/Telegram-Scraper-Adder

<> Step 4: Setup the requirements

cd Telegram-Scraper-Adder
chmod +x Setup.py

<> Step 5: Setup TG accounts for scraping and adding

python Setup.py -c

================================================
To setup API/Hash for TG accounts, please go to my.telegram.org

And login thereby providing your phone number and verification code

If you haven't created any app then create one

Note: please use cloudflare VPN to hide IP address. Telegram check telephone no. location with IP address.

After that click on API-Documentation

Then copy App Id, API Hash

Now go back to Termux and type App Id and hit enter, then it will ask for API Hash, just copy and paste the API Hash and hit enter

It will ask for your Phone number, just give your number (international format) and hit enter that's all your setup is ready

================================================

<> Step 6: Run scraper

python scraper.py

And select any group by typing the number

It will Scrap all the members of the group and will be saved as members.csv

<> Step 7: Run Adder

python Adder.py members.csv

This step is to add TG accounts in members.csv to target groups.
