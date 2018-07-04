`Sniff network traffic from your iOS device, no jailbreak necessary`



```
 $ system_profiler SPUSBDataType|perl -0 -ne'/iP(?:hone|ad):.*?Serial Number: (\S+)/s?`rvictl -s $1`:0' ; sudo tcpdump -i rvi
```

**_Credit: samykamkar_**
