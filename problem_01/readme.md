




# Date: 4th Aug, 2021

## External js problem


### tags are  not used in js files

#### Before (in firstscript.js)
```
<script>
    document.body.innerHTML = '<h1>Working with heading</h1>';
</script>
```

#### Current (in firstscript.js)

```
document.body.innerHTML = '<h1>Working with heading</h1>';
```

Some tips: 
  - Use relative path when including js files
  https://www.youtube.com/watch?v=BMT3JUWmqYY
  - Look into the console for reading errors 
    - For chrome, click ctrl+shift+j

  


### 3.html

Added console.log to make sure the scroll is working, look into the console and try it out


### 2.html 

The javascript used in this segment is based on a library called jquery, you have to include jquery if you're using this syntax







