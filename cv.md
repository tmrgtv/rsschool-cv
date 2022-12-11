# **Timur Gutov**
![My photo](photo.png)

Enginieer

## **My contacts**
Mobile: +7 996 336 79 90
Email: <tmrgtv@gmail.com> 
Discord: [TimurG#2201](https://discordapp.com/users/954363526259028029/)  
Telegram: [@Timur_Gut](https://t.me/Timur_Gut)  
Discord RS School: Timur Gutov (@tmrgtv)  

## **About me**
I work as a multimedia engineer in [ICL Services](https://icl-services.com/). I am engaged in the design and commissioning of conference rooms, meeting rooms and classrooms, museums, trading floors, private houses. Programming Crestron, AMX, Kramer, Aten controllers and some KNX equipment. 

I know a bit about Excel VBA, Power Query and Power BI. I know the SQL language at a basic level. I am also learning the Go language and I know fyne.io, excelize packages. Interested in applying front-end knowledge in multimedia equipment and smart homes. Probably learning programming is my hobby.

## **Education**
**2006-2011** Engineer majoring in "Physics and technology of optical communication" at the Bashkir State University.  
**2021** Completed the [Power BI & Excel PRO](https://netology.ru/programs/excelpbi) course at Netology.  
**2022** Took free courses in Go at [stepik.org](https://stepik.org/course/54403/syllabus) and [Yandex Practicum](https://practicum.yandex.ru/go-basics/).

## **Example code from codewars**
[Take a Ten Minutes Walk](https://www.codewars.com//kata/54da539698b8a2ad76000228/go)
```go
package kata

func IsValidWalk(walk []rune) bool {
  if len(walk) != 10 {
    return false
  }
  var x,y int
  for _,dir := range walk {
    switch dir {
      case 'n':
        x += 1
      case 's':
        x -= 1
      case 'e':
        y += 1
      case 'w':
        y -= 1
    }
  }

  if x == 0 && y == 0 {
    return true
  }
  
  return false
}
```
[Go Playground](https://go.dev/play/p/JOI8LFZA2wb)

## **My project**
[My project](https://github.com/tmrgtv/spider) is a golang package for work with API ["Spider Project"](http://www.spiderproject.com/). It can be used to integrate with databases.

