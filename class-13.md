# Local Storage

[Back to Main Page](README.md)

Back in the "good old days" there was only internet explorer. The only web browser that had the ability to store any amount of userData, a whopping 64 kb. Gradually through the years additional tools were added by various companies that increased the amount of storage capability. Then along came:

## HTML5 Storage

- allows web pages to store values locally within the client web browser

- basically every browser has HTML5 storage at this point

- before using storage it's important to check to see if the browser has storage

- you can write your own function or use Modernizr

- you store data using "named keys" then retrieve them using the same keys

- in js treat localStorage as an associative array

- you can track storage events to keep track of whenever named keys are added, changed or deleted

- 5mb is the default storage amount in browser

- "Quota_Exceeded_Err" gets thrown if you exceed 5mg of local storage

- an example of local storage is a website checking previous progress you've made through it's content and returning you to the same spot
