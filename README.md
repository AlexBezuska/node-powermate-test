# Powermate Servermate


Install dependencies
```bash
npm install
```

Start running the server
```bash
npm start
```


### API usage:

change brightness (range 0-255)  (AJAX PUT)
```
http://0.0.0.0:8081/brightness/187
```



Get the current status of the Powermate (AJAX GET)
```
http://0.0.0.0:8081/status
```

This will return a data object containing:
```javascript
{
  buttonDown: false,
  wheelDelta: 0,
  brightness: 0
}
```
