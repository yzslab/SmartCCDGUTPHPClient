# Smart CCDGUT PHP Client
![](https://zhensheng.im/wp-content/uploads/2018/11/SmartCCDGUTPHPClient.png)
## Requirements
PHP >= 7.0

curl

json

xml

## Usage
Available commands
```
        login [USERNAME] [PASSWORD]             Login to Smart CCDGUT and save token.
        logout USERNAME                 Logout.

        electric USERNAME               Query electric usage details.
        attendance USERNAME             Query attendance details.
        extraCredit USERNAME            Query extraCredit details.
        
        ccdgutAuth USERNAME IP          CCDGUT Network authenticate
```

Login first
```bash
./SmartCCDGUT login [USERNAME] [PASSWORD]
```

Logout
```bash
./SmartCCDGUT logout
```

CCDGUT Network authenticate
```bash
./SmartCCDGUT ccdgutAuth USERNAME IP # e.g. ./SmartCCDGUT ccdgutAuth 201535000000 10.20.0.0
```

Query electric usage details
```bash
./SmartCCDGUT USERNAME [area] [room]
```
![](https://zhensheng.im/wp-content/uploads/2018/11/SmartCCDGUTPHPClient-SelectArea.png)