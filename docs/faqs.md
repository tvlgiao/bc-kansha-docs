# FAQs

## Display the product image on the left column on PDP

Q: On the Product page, flip the product image so that its on the left and the description on the right. (Most US sites are like this)

A:

Go to **Storefront** > **Script Manager**, click **Create a Script**, choose:

- **Location on page** = `Head`
- **Select pages where script will be added** = `All Pages`
- **Script type** = `Script`

Enter the script below to **Scripts contents**:


```html
<script>
(function() {
var style = document.createElement('style');
style.innerHTML = '@media (min-width: 801px) {'
+ '.productView-details { float: right; clear: right; padding-left: 1.5rem; padding-right: 0 }'
+ '.productView-images, .productView-alsoBought--right { float: left; clear: left; padding-left: 0; padding-right: 1.5rem }'
+ '}';
document.head.appendChild(style);
})();
</script>
```

## Display mega menu with 4 columns

Go to **Storefront** > **Script Manager**, click **Create a Script**, choose:

- **Location on page** = `Footer`
- **Select pages where script will be added** = `All Pages`
- **Script type** = `Script`

Enter the script below to **Scripts contents**:

@media (min-width: 801px) {
    .navPage-subMenu-list { grid-template-columns: repeat(4, minmax(max-content,350px)) }
    .navPage-subMenu-item:nth-child(3n) { border-right: 1px solid #d6d6d6 }
    .navPage-subMenu-item:nth-child(4n) { border-right: 0 }
}

```html
<script>
(function() {
var style = document.createElement('style');
style.innerHTML = '@media (min-width: 801px) {'
+ '.navPage-subMenu-list { grid-template-columns: repeat(4, minmax(max-content,350px)) }'
+ '.navPage-subMenu-item:nth-child(3n) { border-right: 1px solid #d6d6d6 }'
+ '.navPage-subMenu-item:nth-child(4n) { border-right: 0 }'
+ '}'
;document.head.appendChild(style);
})();
</script>
```
