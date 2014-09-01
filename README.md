# mycli -- MySQL command line client for dummies

I was tired of trying to remember all of the various command and steps for relatively simple requests in MySQL, so I wrote a simple bash script for those.

## Installing

1. Clone (or download) to directory of your choice
2. Make it executable: `chmod u+x mycli`

## Usage

`mycli <command>`

### Commands

#### list

List databases

#### create

Create a database and, optionally, a database user with full privileges to that database

#### makeuser

Create user and grant privileges

#### export

Export a database to a .sql file