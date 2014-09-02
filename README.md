# mycli -- MySQL command line client for dummies

I was tired of trying to remember all of the various command and steps for relatively simple requests in MySQL, so I wrote a simple bash script for those.

## Installing

1. Clone, download, or use curl to get the script:

`curl -O https://raw.githubusercontent.com/jon-heller/mycli/master/mycli`

2. Make it executable: `chmod +x mycli`
3. Copy to the bin directory: `sudo cp mycli /usr/local/bin/mycli`

## Usage

`mycli [args] <command>`

### Arguments

    -u [username]

MySQL username

    -p [password]

MySQL password

### Commands

#### list

List databases

#### createdb

Create a database and, optionally, a database user with full privileges to that database

#### createuser

Create user and grant privileges

#### export

Export a database to a .sql file
