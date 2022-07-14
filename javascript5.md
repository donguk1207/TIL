# JavaScript 제어문-조건문 
## 🟡문법  
if(조건식){  
     //statement1  
  }else if(조건식){  
    //statement2  
  }else{  
    //statement3  
  }  
  >-if 안에 있는 ```조건식```이 참인 경우 해당하는 if문else if문을 실행 한다.  
  -조건문(if,else if)에 모두 해당하지 않으면 else에 있는 statement3이 실행된다  
  -ele if에는 갯수 제한이 따로 없다. 
  #  
  ## 🟡조건식 거짓으로 취급하는 값  
  1) flase  
  2) undefined  
  3) null  
  4) 0  
  5) NaN  
  6) the empty string("")  
  ```
  ex)if 안의 조건문이 "참"이 아니기 때문에 else문 실행  
  >if(flase){  
    console.lof("flase");  
   }else{  
    console.log("true");  
   }  
   true  
   ```  

   ```
  >if(undefined){  
    console.lof("flase");  
   }else{  
    console.log("true");  
   }  
   true  
   ```

```
    >if(null){  
    console.lof("flase");  
   }else{  
    console.log("true");  
   }  
   true  
 ```  

 ```
   >if(0){  
    console.lof("flase");  
   }else{  
    console.log("true");  
   }  
   true  
```  
```
  >if(NoN){  
    console.lof("flase");  
   }else{  
    console.log("true");  
   }  
   true  
```  
##  🟡조건문에서 사용할 수 있는 비교 연산자  
  
 * ===,!== :한 값이 다른 값과 같거나 다른지 판다 한다.  
 * <,> :한 값이 다른 값보다 작은지 큰지 판단 한다.  
 * <=,>= :한 값이 다른 값보다 작거나 같은지, 크거나 같은지 판단 한다.  
 #  
 ## 🟡if문의 중첩  
 -if문은 중첩시켜 사용할수 있다.  
 ```
 var score = 96;  
 var lecture "sports";  

 if("storts" == lecture){  
         if(score >= 70){  
               console.log("점수 : pass");  
        }  
         else{  
               console.log("점수 : fail");  
        }  
}  
else{  
      if(score >= 90){  
            console.log("점수 : A");  
      }else if(score >= 80){  
            console.log("점수 : B");  
      }else if(score >= 70){  
            console.log("점수 : C");  
      }else if(score >= 60){  
            console.log("점수 : D);  
      }else{  
            console.log("점수 : F");  
      }  
}  
점수 : pass  
```  
## 🟡switch문 
switch (변수){  
    case A: //값 A  
    //변수 값이 A일때 실행할 명령문  
    break; 
    case B: //값 B  
    //변수 값이 B일때 실행할 명령문  
    break;  
    case C: //값 C  
    //변수 값이 C일때 실행할 명령문  
    break;  
    default:  
    //모든 CASE에 부합하지 않을때 실행할 명령문  
    break;  
}  
#  
## 🟡삼항연산자  
-간단한 if문이나 switch문들을 간결하게 바꾸어 삼항연산자를 이용할 수도 있다.  
```
var num = 3;  
(num > 0) ? console.log('양수!') : console.log('음수!');  
양수!
```  
```
var num = 3  
var result = num > 0 ? "양수" : "홀수";  
console.log(result);//양수  
양수
```


            
