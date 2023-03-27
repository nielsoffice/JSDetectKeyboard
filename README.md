# JSDetect_Keyboard
<br /> JavaScript Detect Keyboard current press using EventListener "keydown"
<br /> Reference:
<br /> https://developer.mozilla.org/en-US/docs/Web/API/Element/keydown_event 

```JS
   
   document.addEventListener('keydown', function (e) {

    // Detect which keyboard are currently press
    // Read the keyboard property { isTrusted: true, key: 'enter', code: 'keyEnter' }
    console.log(e);
    // access property via dot notation JS ex. e.key
    console.log(e.key);

    // Usage: 
    if(e.key === 'Escape') {
       console.log(e.key);
       // do something! ...
    }

   });
   
```

<br /> Also EventListener "Keyup" 
<br /> Reference: 
<br /> https://developer.mozilla.org/en-US/docs/Web/API/Element/keyup_event <br />


```JS
 // JavaScript Event
 https://developer.mozilla.org/en-US/docs/Web/Events
```
