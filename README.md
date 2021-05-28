# discord-eth-token-holders
a discord bot to show you the number of holders for a particular ethereum token

![image](https://user-images.githubusercontent.com/7338312/120041575-19166b80-bfce-11eb-98bb-f0babc829ccd.png)

## usage

```
  -activity string
        text for activity
  -address string
        address of the token contract
  -frequency int
        seconds between gas price cycles (default 5)
  -header string
        text for nickname
  -setNickname
        wether to set nickname of bot
  -token string
        discord bot token
```

```
./discord-eth-token-holders -token 'xxxxxxxxxxxxxxxxxxxxxxxxx' -address '0x0000000000000000000000000' -activity '000 Holders' -header 'Total: ' -setNickname
```
