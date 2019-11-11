# QueerJs - Bookmarklets!
A list of (hopefully) use bookmarklets as outlined in my 2019 QueerJS talk

## onbrand query param
adds a query parameter to the end of the current url

```js
javascript: (function() {window.location.href += "?onbrand";})();
```

## css debug
use this to add an outline of hotpink to all elements in the body

```js
javascript: (function() {document.body.querySelectorAll("*").forEach(element => (element.style.outline = "1px solid hotpink"));})();
```

## github code review
use this to add a cute donger to the review changes textarea on the Files Changed page of a Pull Request

```js
javascript: (function() {const dongerList = ["c( ⁰ 〰 ⁰ )੭","ᕙ( ~ . ~ )ᕗ","░ ∗ ◕ ں ◕ ∗ ░","(ﾉ◕ヮ◕)ﾉ*:･ﾟ✧","╰(◕ᗜ◕)╯","(◕ᴥ◕)","( ͡↑ ͜ʖ ͡↑)"];document.getElementById("pull_request_review_body").value =dongerList[Math.floor(Math.random() * dongerList.length)];})();
```
