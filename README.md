# gnu-social-translation

This repository serves as a mirror of the GNU social [translation project](https://www.transifex.com/projects/p/gnu-social/) on Transifex. The main GNU social code repository is [here](https://gnu.githost.io/gnu-social/social).

### Instructions - how to use the translations:

1. Make sure you have **Git** and **GNU Make** installed. On Ubuntu, or similar linux distribution, use `sudo apt-get install git make`
2. Clone this repository using `git clone https://github.com/digital-dreamer/gnu-social-translation.git`, or if you already cloned it some time ago, update it using `git pull`
3. Copy the 2 folders you see in the cloned repository (`locale` and `plugins`), and paste them into the folder where you installed your GNU social instance.
4. Go to that folder (where GNU social is installed) and run this command: `make translations`

If you encounter any problems, please go to the issues section of this repository and open a new issue.

-----

[GNU social](http://gnu.io/social/) is a decentralized social network software that you can install on your own server. We give you the freedom to reveal as much, or as little, information about you to other sites as you wish... True to GNU itself, social is licensed under the GNU Affero General Public License. 
