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
```

Login first
```
./SmartCCDGUT login [USERNAME] [PASSWORD]
```

Logout
```
./SmartCCDGUT logout
```

Query electric usage details
```
./SmartCCDGUT USERNAME [area] [room]
```
![](https://zhensheng.im/wp-content/uploads/2018/11/SmartCCDGUTPHPClient-SelectArea.png)