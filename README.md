# Show-my-ip-and-friendly-report
![Mozilla Add-on](https://img.shields.io/amo/users/show-ip)

Add-on link (Firefox): https://addons.mozilla.org/en-US/firefox/addon/show-my-ip-friendly-report/

- Main API: https://twin.sh/api/v1/ip
- FALLBACK API: http://ip-api.com/line?fields=query


## Build
```
web-ext build
```


## Notes
Special thanks to http://ip-api.com for letting me use their API as a fallback in case the main API goes down.
