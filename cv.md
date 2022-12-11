# **Timur Gutov**
![My photo](photo.png)

Enginieer

## **My contacts**
Mobile: +7 996 336 79 90  
Email: <tmrgtv@gmail.com> 
Discord: [TimurG#2201](https://discordapp.com/users/954363526259028029/)  
Telegram: [@Timur_Gut](https://t.me/Timur_Gut)  
Discord RS School: Timur Gutov (@tmrgtv)  

## **Example code from <https://www.codewars.com/>**
>package kata
> 
>func IsValidWalk(walk []rune) bool {  
>  if len(walk) != 10 {  
>    return false  
>  }  
>  var x,y int  
>  for _,dir := range walk {  
>    switch dir {  
>      case 'n':  
>        x += 1  
>      case 's':  
>        x -= 1  
>      case 'e':  
>        y += 1  
>      case 'w':  
>        y -= 1  
>    }  
>  }  
> 
>  if x == 0 && y == 0 {  
>    return true  
>  }  
> 
>  return false  
>}  