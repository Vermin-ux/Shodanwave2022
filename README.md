# Shodanwave2022
Working except that the results are not encoded, which could cause a crash Shodanwave is for IP cameras, and it will attempt brute-force attacks using the list and usernames provided. Enjoy your spying.
Installation
$ cd /opt/
$ git clone https://github.com/fbctf/shodanwave.git
$ cd shodanwave
$ pip install -r requirements.txt
Usage
Usage: python shodanwave.py -u usernames.txt -w passwords.txt  -k Shodan API key --t OUTPUT
       python shodanwave.py --help 
         __              __                                   
   _____/ /_  ____  ____/ /___ _____ _      ______ __   _____ 
  / ___/ __ \/ __ \/ __  / __ `/ __ \ | /| / / __ `/ | / / _ \
 (__  ) / / / /_/ / /_/ / /_/ / / / / |/ |/ / /_/ /| |/ /  __/
/____/_/ /_/\____/\__,_/\__,_/_/ /_/|__/|__/\__,_/ |___/\___/ 
                                                              

This tool is successfully connected to shodan service
Information the use of this tool is illegal, not bad.

usage: shodanwave.py [-h] [-s SEARCH] [-u USERNAME] [-w PASSWORD] [-k ADDRESS]

optional arguments:
  -h, --help            show this help message and exit
  -s SEARCH, --search SEARCH
                        Default Netwave IP Camera
  -u USERNAME, --username USERNAME
                        Select your usernames wordlist
  -w PASSWORD, --wordlist PASSWORD
                        Select your passwords wordlist
  -k ADDRESS, --shodan ADDRESS
                        Shodan API key
  -l LIMIT, --limit LIMIT
                        Limit the number of registers responsed by Shodan
  -o OFFSET, --offset OFFSET
                        Shodan skips this number of registers from response
  -t OUTPUT, --output OUTPUT
                        Save the results
  -p, --tor
		        All Requests/Wgets go through Tor 
	                

Attention
Use this tool wisely and not for evil. To get the best performece of this tool you need to pay for shodan to get full API access Options --limit and --offset may need a paying API key and consume query credits from your Shodan account.
