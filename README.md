# test-project
Git 연습용 프로젝트
## 실습 언어

파이썬

### h3 급 제목
---
구분선 "---"
---

### 마크다운 리스트 만드는법
- 리스트 1
- 리스트 2
  - 하위리스트1
  - 하위 리스트 2
-리스트 3
### 체크리스트 만드는법
- [ ] 체크항목1
- [x] 체크항목2 체크된 상태
- [ ] 체크항목3
## 코드 넣는법 ```

### 파이썬에서 HelloWorld!
```python
name = input('이름을  입력하세요:')
print(name, '님 환영합니다!')
```
### Java의 HelloWorld!
```java
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello, World!");
    }
}
```
### 강조
 - 문장 사이에 어떤 코드를 강조할 때: 변수 `name`에는 이름이 저장된다.
 - 강조 할때 **굵게** 하고 싶으면

### 하이퍼 링크 넣는법
- [여기를 누르세요](https://tortoisegit.org/)

### 이미지 넣는법
- ![고양이 이미지](https://marketplace.canva.com/8-1Kc/MAGoQJ8-1Kc/1/tl/canva-ginger-cat-with-paws-raised-in-air-MAGoQJ8-1Kc.jpg)
### 레포지토리에 있는 이미지 넣을경우
!(상대경로.jpg)

### 표 만들기

| 헤더1 | 헤더2 | 헤더3 |
|---|---|---|
|셀1|셀2|셀3|
|셀1|셀2|셀3|
|셀1|셀2|셀3|

### 인용문
> 산은 산이요 물은 물이로다.
> <br>일찍 일어나는 벌레가 빨리 잡아먹힌다.

### 깃 활용법
 - 저장소 생성 : 원격(github) -> 로컬(pull)
 - A 소스코드 수정
 - git add * (staged로 변경)
 - git commit -m "~~수정" (변경사항 커밋)
 - -> 로컬
 - git push (원격 저장소로~)
 - git pull **(항상 시작 하기전에 하고 실행 해야한다)** 최신버전 기준으로 B컴에서 소스 수정
 - git add * (staged로 변경)
 - git commit -m "~~수정" (변경사항 커밋)
 - -> 로컬
 - git push (원격 저장소로 ~)




