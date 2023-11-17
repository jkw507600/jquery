# jquery 기본 연습

## jquery basic
 - animate ()
 ```
 $('.btn1').on('click',function(){
            $('.text1').animate({marginLeft:500, fontSize:30},2000,function(){
                alert('hellooooo')
            })
        })
```
 - fade()
```
 $('.btn1').on('click',function(){
            $('.box').slideUp(1000,'linear',function(){ //linear 안쓰고 그냥 두면 swing (천천히-빨리-천천히)효과
                $('.btn1').hide()
                $('.btn2').show()
            })
        })
``````        

mockaroo 목업데이타 사이트
https://www.mockaroo.com/