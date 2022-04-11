# Coding_Style
개인적인 코딩 스타일을 정의하기 위한 정리 문서

- BSD 스타일의 괄호 스타일을 사용한다

```
main()
{
code...
}
```

------------------------------

# 변수/함수 작성 스타일

## 변수/함수 표기법
파스칼 표기법 + 스네이크 표기법
- 스네이크 표기법: 공백을 언더바로 표시
- 파스칼 표기법: 단어 첫 문자는 대문자로 작성


```
ex) Pascal_Snake
```


## 변수 초기화
비야네 스트롭스트룹의 조언에 따라 변수는 선언과 동시에 초기화 


```
int temp = 0;
```


## 들여쓰기

2,3차원 배열의 경우 각 배열 요소를 IDE에서도 확인하기 쉽게 들여쓰기와 행 나누기
```
array [3][3] = { 1, 2, 3
                 4, 5, 6 
                 7, 8, 9 } 
```


------------------------------


# 주석


- 코드를 처음 보는 사람도 이해하기 쉽도록 작성한다.
- 코드를 분석하는 시간을 줄이도록 필요하다면 주석 내용을 길게 작성한다.
- 블럭 주석은 사용하지 않고 더블슬래시의 한줄 주석만 사용한다.
 
------------------------------

# 디자인 패턴
