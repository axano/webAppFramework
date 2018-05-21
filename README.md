```

   __________-------____                 ____-------__________
   \------____-------___--__---------__--___-------____------/
    \//////// / / / / / \   _-------_   / \ \ \ \ \ \\\\\\\\/
      \////-/-/------/_/_| /___   ___\ |_\_\------\-\-\\\\/
        --//// / /  /  //|| (O)\ /(O) ||\\  \  \ \ \\\\--
             ---__/  // /| \_  /V\  _/ |\ \\  \__---
                  -//  / /\_ ------- _/\ \  \\-
                    \_/_/ /\---------/\ \_\_/
                        ----\   |   /----
                             | -|- |
                            /   |   \
                           |___/ \___|
  _____ _               _____  _____ ______ _____ ______ _____
 / ____| |        /\   |  __ \|_   _|  ____|_   _|  ____|  __ \
| |    | |       /  \  | |__) | | | | |__    | | | |__  | |__) |
| |    | |      / /\ \ |  _  /  | | |  __|   | | |  __| |  _  /
| |____| |____ / ____ \| | \ \ _| |_| |     _| |_| |____| | \ \
 \_____|______/_/    \_\_|  \_\_____|_|    |_____|______|_|  \_\


```
# CLARIFIER

Command Line Advanced ReconaIssance FootprInting and EnumeRation tool .

This tool is a meta tool made for making web pentesting more efficient.

This project is an implementation of the reconnaissance, footprinting and enumeration phase of https://github.com/axano/HackersUniversity/blob/master/WebApplicationPentestingCheatSheet

## Getting Started

### Prerequisites

This tool is designed to work and tested on kali linux 2017.3.

Using this tool on another OS may be a pain in the a**.

Refer to manual.txt for the installation proccess of each packet.
```
host
wget
curl
nmap
curl
cutycapt
sed
awk
getopts
Aquatone --> https://github.com/michenriksen/aquatone
dirb
```
### Installation and usage
```
On Kali 2017.3 >= the only program that has to be installed is aquatone.
gem install aquatone
git clone https://github.com/axano/CLARIFIER.git
cd CLARIFIER
./main -d example.com 
```
## Authors

Emmanouil Perselis A.K.A AXANO

## License

This project is licensed under the GNU GPLv3 licence - see the [LICENSE](LICENSE) file for details

## Acknowledgments


## TODO


Add noise/risk levels.

Add subdomain takeover scanner.

Add automated SQLMap scan ?

Add tests to check if certain test is successful

## AUTO GENERATED PART
### current line count head
```
    4 .gitignore
  674 LICENSE
   56 README.md
   68 lib/checks/arguments.sh
   64 lib/checks/internet.sh
   41 lib/checks/prerequisites.sh
   11 lib/checks/system.sh
  114 lib/interface/decoration.sh
   34 lib/phases/advancedFootprinting.sh
  102 lib/phases/footprinting.sh
   34 lib/phases/initialization.sh
   36 lib/phases/reconnaissance.sh
   38 lib/uncategorized/housekeeping.sh
  111 main.sh
   81 manual.txt
   11 usage.txt
 1479 total
```
### current line count tail
