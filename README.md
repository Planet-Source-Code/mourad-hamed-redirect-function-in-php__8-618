<div align="center">

## Redirect Function in PHP


</div>

### Description

Redirect, via simple function.
 
### More Info
 
just page name :)

Its just a function to redirect, to whatever page you need, just pass the parameter to the funtion.

redirect action


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Mourad Hamed](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/mourad-hamed.md)
**Level**          |Beginner
**User Rating**    |3.8 (15 globes from 4 users)
**Compatibility**  |PHP 3\.0, PHP 4\.0
**Category**       |[Complete Applications](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/complete-applications__8-7.md)
**World**          |[PHP](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/php.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/mourad-hamed-redirect-function-in-php__8-618/archive/master.zip)





### Source Code

```
function Redirect_Function($Page)//Function to redirect the page into destination one due to its parameter
  {
   global $HTTP_SERVER_VARS;
   $Path = "http://".$HTTP_SERVER_VARS['HTTP_HOST'].dirname($HTTP_SERVER_VARS['PHP_SELF'])."/".$Page;
   echo"<script>window.location=\"$Path\"</script>";
  }
```

