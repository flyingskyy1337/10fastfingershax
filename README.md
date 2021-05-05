# 10fastfingershax
10ff.net and 10fastfingers.com hacks here.

# What is the difference between 10ff.net and 10fastfingers.com

10ff.net is a multiplayer typing race, while 10fastfingers.com is a type test.

# How do I activate the hack?
In 10ff.net just paste it anyway even before the start, the hax will activate when race is begun.
In 10fastfingers.com in the other hand also paste it anyway.
But where do I paste it you ask? In the Developer Tools (CMD+Opt+I or Win+Alt+I) you click Console and paste the code that works
with 10ff.net or 10fastfingers.com, the codes are different so they don't work on for example 10ff code into 10fastfingers, or
10fastfingers code to 10ff.net

# Codes.

10FASTFINGERS.COM CODE
```javascript
var input = $('#inputfield')[0]
var ev = $.Event('keyup')
ev.which = 32
setInterval(function() {
    if ($('.highlight')[0]) {
        input.focus()
        input.value = $('.highlight').text()
        $(input).trigger(ev)
    }
}, 100)
```

10FF.NET CODE
```javascript
const highlight = document.getElementsByClassName("highlight");
const input = document.getElementsByTagName("input")[0];
const event = new InputEvent("input", {data: "k"});

setInterval(() => {
    if (highlight.length > 0) {
        input.value = highlight[0].innerText + " ";
        input.dispatchEvent(event)
    }
});
```

# 2k21 flyingskyy
