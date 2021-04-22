


# SOL 선행 업무 LIST

## 위험률 

 * 위험률 갯수 확인 
    1) 위험률DB전체 data	
    2) 실제 사용하지 않는 위험률 갯수 
    3) mapping이 필요한 위험률 갯수 
       - 현재는  갱신 담보 위주로 맵핑을 하려고 하나 그렇게 해도 될까?
          
 * 위험률 유형 구분 
    - 구분자가 많아서 빼놓은 재물 위험률
    - 이차암
    - 일반 
       - 구분자가 바뀌는 경우(아래 datalinnk정보와 유사한 정보)
       - 손해율 가정으로 인해 원래 

## 맵핑이 필요한 data 

* risk rule 정보
   - 위험률 조합을 현재 프로펫 내부의 rule을 체크할 수 있는지 확인
* datalink 정보
   - layout의 유효값과 위험률 구분자의 유효값이 다른 경우 어떻게 해야할지? mapping table 이용
* 상품정보 > 담보정보 > 급부정보
   -  납면정보가 우리 8개 납면 rule 위험률 
 
	 ```
	 a 담보) 독립인 경우는 8개 가장 기본적인 납면 rule
	 b 담보) 탈퇴가 있고 이재소멸 담보의 경우에는 납면 rule이다르고 위험률     
   ```
	 
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE1NzA5MDcyNTMsLTYwMjI5OTgyNCwtMT
MxNDQ1NDk0Nl19
-->