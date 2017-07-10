# LiquidPlanner-Bookmarklets
Contains a collection of JavaScript bookmarklets for LiquidPlanner.

**License:** GNU General Public License v3.0

Please submit a Pull Request if you'd like to suggest an improvement. Minified code is generated by pasting the JavaScript source into [this converter](http://jpillora.com/bookmarkleter/).

# Install

Updates are manual, due to [Content Security Policy](https://developer.mozilla.org/en-US/docs/Web/HTTP/CSP) in most modern browsers. Check back here for updates.

**Google Chrome**
1. Show bookmark bar (Cmd+Shift+B if hidden)
2. Right Click > Add Page...
3. Enter any 'Name' and 'URL' as per code block below.

## ShowIDs

```
javascript:(function(){var%20tasks=document.getElementsByClassName('task_row%20large_row');for(var%20i=0;i%20%3C%20tasks.length;i++){var%20taskID=tasks[i].getAttribute('data-item-id');var%20timerElement=tasks[i].getElementsByClassName('timer_column')[0];timerElement.innerHTML='%3Cspan%20style=%22font-size:1.5em%22%3E'+taskID+'%3C/span%3E';}})();
```