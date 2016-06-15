# wifidump

## install

install wifidump via homebrew:
```shell
  $ brew tap ironbiff/wifidump
  $ brew install wifidump
```

## commandline options
Several options are available using the command line:

    -v            show current version


## versions

### 0.3
- change parsing line selection from sed to grep
- remove __bandwidth__ because of wrong and unimportant imformation
- add some styling
- wording
- adding time and date
- catching iperf errors
- add -v parameter for current version

### 0.2
- rename file from wifi\_dump.sh to wifidump

### 0.1
- initial output with:
  * __name__ of client
  * __mac__ address of client
  * network __ssid__
  * __mac__ of access point
  * last __transmistion rate__
  * current __channel__
  * connections __bandwidth__
  * __iperf__ result summary
- provide via homebrew