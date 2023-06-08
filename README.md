# 마크다운

## Heading


## List

## Fenced Code Block

```
언어 저장하지 않고 표현
```


```python
# 주석
print('hello')
```

```html
<!--주석-->
# 파이썬 주석
<h1>마크다운</h1>
```

## 링크

-[구글](https://google.com)

-[파이썬](./python.md)

## 이미지

![이미지] (./image.png) 

## 표



## 텍스트
*기울임* **굵게** ~~취소선~~

---
안녕하세요
---
git add .
git commit -m "success" #m 뒤에는 아무 메시지나 타이핑해야함
git push origin main
이게 수정사항을 깃에 업로드하는 순서

1. 내가 작업을 완료하고 버전으로 기록하기 위해 실행하는 명령어를 작성하라
git add <file/directory>
git commit -m 'message....'
=============
git push origin main #원격 저장소에 보내기 위한 명령어

2. Untracked : 한번도 커밋이 된 적 없는 파일
    Changes not staged for commit : 변경사항들이 commit 되지 않았다
   nothing to commit, working tree clean : 커밋할것이 없고 작업공간은 깨끗한 상태이다.

3. git은 무엇인가 : 공유, 업로드 되어있는 코드들을 받아올 수 있게 해주는 도구, 내 코드들을 저장, 업로드 할 수 있게 도와주는 도구.

4. github는 무엇인가 :내 코드를 저장하는 공간, 소스코드를 공유하는 공간, 협업하는 공간

https://www.youtube.com/watch?v=FaV0tIaWWEg


#merge 하고서 그래프로 보는것
git log --online --graph

명령어 정리
git branch {branch name}
git checkout {branch name}


#변경 사항을 로컬이 아닌 다른 브랜치로 보내는 법>??!!



#git pull origin main

1.가져오고 싶은 깃허브 주소에서 우측 상당 fork 클릭하고 create fork
2.원격 저장소를 clone해야하는데 본인의 저장소를 clone할것
git clone https://github.com/~~~~~/가져올 원격저장소 파일이름이 있을거임
3.바탕화면에 가져올 파일 이름 폴더 생기면 vscode로 열기
4.파일 불러온 후 작업 후 commit
5.git push origin main
6.git hub접속해서 pull request 만들기
https://github.com/JooChanYoung/git-0608
