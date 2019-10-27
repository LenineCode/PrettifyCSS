# Prettify CSS #


## Documentation##

**Table of content**
- [Grid System](#grid-system)

### Grid System ###

To create a grid row use the .row class  
```
<div class="row"></div>
```

By default the row overflow is not collpased. If there are more than 12 columns in a row, those in excess are moved on the bottom respecting row spacement (it behaves like a new row).  
You can cancel this by using the .overflow-collapse class.  
``` 
<div class="row overflow-collapse></div>
```  
  
To fill the rows use .s1 to .s12 classes.
```
<div class="row overflow-collapse>
    <div class="s1">elem</div>
    <div class"s4">elem</div>
</div> 
```  

The grid can be responsive (using mobile-fist system)  
simply add .m1 to .m12 (for medium devices and up) and/or .l1 to .l12 (for large devices).

```
<div class="row overflow-collapse>
    <div class="s12 m6 l3">elem</div>
    <div class"s12 m6 l3">elem</div>
</div> 
```

You can create offset between elements using offset classes :
 * offset-s1 to offset-s12 for the small devices and up.
 * offset-m1 to offset-m12 for the medium devices and up.
 * offset-l1 to offset-l12 for the larges devices.

```
<div class="row overflow-collapse>
    <div class="s6 m4">elem</div>
    <div offset-m4></div>
    <div class"s16 m4">elem</div>
</div> 
```

You can specifies a specific start column using :  
 * start-s1 to start-s12 for the small devices and up.
 * start-m1 to start-m12 for the medium devices and up.
 * start-l1 to start-l12 for the larges devices.