# git



#### init

git init 활동폴더를 master git에 등록하고 master화 시킴(초기화)



#### status

git status 깃의 현재 상태를 보는 명령어

추가된 파일이나 수정된 파일 포함되어있지 않은 파일등을 확인할수있다.

#### add

git add : staging area에 파일을 추가하는 명령어



#### commit

git commit -m "title"

-m은 메시지를 보낸다는 뜻 commit쓸때 항시 쓴다고 보면 됌

staging area의 파일들을 local repo에 저장시키는 명령어



#### config --globla

사용자를 들록하는 명령어??

git config --globla : user.email "github이메일" 

git config --globla : user.name "gitgub 이름"

--local도 있음



#### log

git commit 의 히스토리 보는 명령어

log --oneline하면 짧게 볼수있음

#### diff

git commit 한후 변경된점이 있는지 확인하는 명령어



#### remote add origin (url)

git remote add origin (url)

remote란 리모트 저장소에 url값이 저장됀 origin을 추가해라 라는 명령어



#### push

git push origin master

master를 origin이 가진 url쪽에 넣어라

최종 github쪽으로 파일을 보내고 저장시키는 명령어

Commit을 이용해 저장한걸 push를 이용해 github의 remote repo에 업로드 한다

