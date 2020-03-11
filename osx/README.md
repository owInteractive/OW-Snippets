## OSX

Clean DNS and restart Network cache

```
sudo dscacheutil -flushcache;sudo killall -HUP mDNSResponder;
```