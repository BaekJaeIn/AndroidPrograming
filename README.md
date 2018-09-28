# git 명령어, markdown 문법 정리
### 2015261034 백재인
***
## git 명령어 정리
1. **전역 설정 정보 조회**
> git config - -global - -list
2. **전역 설정 정보 삭제시키기**
> git config --global --unset-all user.email

> git config --global --unset-all user.name
3. **새로운 저장소 초기화하기**
> git init
4. **저장소 복제하기**
> git clone <저장소 url>
5. **새로운 원격 저장소 추가하기**
> git remote add <원격 저장소> <저장소 url>
6. **새로운 파일 git에 등록시키기(staging)**
> git add <파일>
7. **현재까지 작업한 내용 저장하기**
> git commit -m “<메시지>”
8. **원격 저장소에서 합치지 않고 지역 브랜치로 변경 사항 가져오기**
> git fetch <원격 저장소>
9. **원격 저장소에서 변경 사항을 가져와 현재 브랜치에 합치기**
> git pull <원격 저장소>
10. **새로운 로컬 브랜치를 원격 저장소에 푸싱하기**
> git push <원격 저장소> <지역 브랜치>
***
## markdown 문법 정리
1. **제목(Headers)**
가장 많이 쓰게 되는 서식 중 하나입니다. 제목은 `# 문자로 표현합니다.

'# 가장 큰 제목 (H1)'
# 가장 큰 제목 (H1)
'## 두 번째 수준 제목 (H2)'
## 두 번째 수준 제목 (H2)
'### 세 번째 수준 제목 (H3)'
### 세 번째 수준 제목 (H3)
***
2. **인용(Blockquotes)**
본문 중 인용된 글을 표시하고자 할 때, > 기호를 모든 줄 앞에 써줍니다. 모든 줄 앞에 써줘야 예쁘게 보여요.

예)

'> 인용되는 글입니다.'

'> 인용되는 글의 두 번째 줄.'

'> 인용되는 글의 세 번째 줄.'

위와 같이 쓰면 아래와 같이 표시됩니다.

> 인용되는 글입니다.

> 인용되는 글의 두 번째 줄.

> 인용되는 글의 세 번째 줄.

줄 하나하나마다 엔터치지 않고 그냥 한 문단이 길게 이어져 있는 경우에 문단의 맨 앞에 한 번만 > 기호를 넣어줄 수도 있습니다.

예)

> 두 문단으로 구성된 글을 인용합니다. 두 문단으로 구성된 글을 인용합니다. 두 문단으로 구성된 글을 인용합니다. 두 문단으로 구성된 글을 인용합니다.
> 두 문단으로 구성된 글의 두 번째 문단입니다. 두 문단으로 구성된 글의 두 번째 문단입니다. 두 문단으로 구성된 글이 두 번째 문단입니다.
위와 같이 쓰면 아래와 같이 보이게 됩니다.
두 문단으로 구성된 글을 인용합니다. 두 문단으로 구성된 글을 인용합니다. 두 문단으로 구성된 글을 인용합니다. 두 문단으로 구성된 글을 인용합니다.
두 문단으로 구성된 글의 두 번째 문단입니다. 두 문단으로 구성된 글의 두 번째 문단입니다. 두 문단으로 구성된 글이 두 번째 문단입니다.
그리고 >> 처럼 꺽쇠 기호를 더하면 들여쓰기 수준이 늘어나게 됩니다. 그리고 인용문 안에서 다른 MarkDown 문법을 중복 적용하는 것도 가능합니다.
예)
> 인용되는 첫 번째 줄입니다.
>> 인용되는 내용 안에서 다시 인용되는 부분입니다.
> (인용 수준을 변경할 때 이렇게 빈 줄 하나 넣어주세요)
> 꺽쇠 한 번만 쓰면 다시 상위 수준으로 표시됩니다.
> ## 큰 제목도 인용 안에서 표시 가능합니다.
위와 같이 쓰면 아래처럼 표시됩니다.
인용되는 첫 번째 줄입니다.
인용되는 내용 안에서 다시 인용되는 부분입니다.
꺽쇠 한 번만 쓰면 다시 상위 수준으로 표시됩니다.
큰 제목도 인용 안에서 표시 가능합니다.
