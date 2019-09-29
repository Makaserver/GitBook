#1.2 채팅창에 HelloWorld띄우기

##준비하기
에디터는 뭘 쓰셔도 상관이 없습니다!
컴퓨터에 기본적으로 내장되어 있는, 메모장을 사용하셔도 좋고, [notepad++](https://notepad-plus-plus.org/downloads/) 또는 [sublimetext3](http://www.sublimetext.com/3)를 사용하셔도 무관합니다
그리고, 플러그인은 [여기](https://docs.skunity.com/downloads)에서 다운 하시고, 서버 플러그인 폴더 안에 넣으시면 되겠습니다

##실전
자, 그럼 이제 본인이 설치한 에디터를 열어서, 다음과 같이 작성해 보세요

```JavaScript
command /HelloWorld:
    trigger:
        mesage "HelloWorld"
```

그리고, 이제 저장을 할껀데, 플러그인 폴더에 Skript라는 폴더 안에 있는데, 그 Skript 플더 안에 있는 scripts 폴더 안에
`HelloWorld.sk`라고 저장을 해주세요
그리고, 서버를 열고 서버에 접속해

```JavaScript
/sk reload HelloWorld
```

라고 입력해보세요! 그리고 난후,

```JavaScript
/HelloWorld
```

라고 명령어를 치시면,
짠!
HelloWorld라는 글자가 채팅창에 나오게 됩니다. 현재는 이게 무슨 뜻인지 모르셔도 상관 없습니다! 하지만, 이 강좌가 끝나는 그 순간, 우리는
방금 친 3 줄의 코드가 무슨 뜻인지를 알 수 있게 될 겁니다
