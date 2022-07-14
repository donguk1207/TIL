# **```제어할 태그 선택하기```**  
>< input type = "button" valye = "day" onclick="">  

#
## **onclicl부분에서 body태그를 선택하게 하고 싶은데 어떻게 할까...**  
>=>document : 이 문서에서  
=>query : 웹브라우저에게 질의  
=>Selector : css의 셀렉터 
=>(".myclass") : 선택할 클래스  

**이를 바탕으로 코드를 써본다.  
>document.querySelector('body')  
#
**body태그의 style이라는 속성을 js로 어떻게 넣을까...**  
=> .style을 추가하면 된다.  
**body 태그의 style을 background-color:black으로 지정하고 싶다.  
#
=>.style 뒤에 backgroundColor="";을 추가하면 된다.  
> <input type="button" value="night" onclick="document.querySelector('body').style.backgroundColor='black';>  
#
**택스트 색을 하얗게 바꾸려면?**  
>ocument.querySelector('body').style.color='white';  

.style 뒤에 .color을 붙여준다. 

#
## **CSS를 동적으로 변경하여 사용자와 상호작용할 수 있는 주간모드와 야간모드를 만들 수 있는 능력을 갖추게 되었다.**