# git-hub 특강 1

---

  프로그래밍 배움 이유 

life hacking programming hacking



파이썬 

오픈소스 => 프로그래밍이 쉬워졌다.

오픈소스 ㅣ 제작자의권리를 지키면서 누구나 코드 열람이 가능한, 오픈소스 라이센스 등장

만들어진거 잘 활용하기 

API | 다른 시스템 간의 커뮤니케이션 방식 // 서비스간 대화방식

web에서의 커뮤니케이션 방식 - 요청과 응답(디스플레이 화면)

오픈소스 API



github

두려움을 깨라 

- 오류메세지 ( 긁어서 구글에 던져라 ) => 읽어나갈려는 시도를 해라

coursera - Andrew-stanford Univerity 머신러닝 이론 통계 강의

edx - 컴퓨터공학개론 에 대한 접근 (easy 하게) 기초를 훏는 강의

**파이썬 코딩도장**

udacity.com - machine learning / robotics : hot tech || siraj raval 머신러닝 딥러닝 기술 - youtube

python gta 5 (자율주행 자동차) 

khanacademy.org = 

모두를 위한 딥러닝 

코딩테스트 준비 - 백준온라인 . 백준알고리즘 // 프로그래머스 - 코딩테스트 연습

파이썬 R - HackerRank // 하루에 하나씩



# GIt

---

>  (용어정리) 분산형버전관리시스템 (DVCS) 
>
> 소스 코드의 이력이 기록됨

## 기본 명령어

---

1. git 저장소 (`repository`) 초기화

   ```cmd
   $ git init # commend line interface에서 기입 - '$'
   
   Initialized empty Git repository in C:/Users/user/Desktop/TIL/.git/
   #결과 도 정리 해둬야 복습의 질 향상됨
   ```

   - 원하는 폴더를 저장소로 만들게 되면, `git bash`에서는 `(master`)라고 표기된다. 
   - 숨김 폴더로 `.git/` 이 생성된다.

2. commit 할 목록에 담기 (Staging Area)

   ```cmd
   $ git add. 
   ```

   - 현재 작업공간 (working Directory /Tree)의 변경사항을 commit목록에 추가한다. (add)
   - `.` 리눅스에서 현재 디렉토리(폴더)를 표기하는 방법으로, 지금 내 폴더 에 있는 파일의 변경사항을 전부 추가한다는 뜻으로, 
   - 만일 git.md 파일만을 추가하려면, `git add git.md`로 추가할수 있다.
   - 만일 myfolder폴더를 추가하려면, `git add myfolder/` 로 폴더 내의 모든 파일을 추가할수 있다.

3. commit 하기

   ```cmd
   $ git commit -m '____________'
   ```

   - 커밋 할 때에는 해당하는 버전의 이력을 의미하는 메시지를 반드시 적어준다. 
   - 메세지는 지금 버전을 쉽게 이해 할수 있도록 작성한다
   - 커밋은 현재 코드의 상태를 스냅샷 찍는 것이다.

4.  로그 확인하기 

   ```cmd
   $ git log
   commit f7e12ea6103c1959f4d74dabd98afba4f33c04b3 (HEAD -> master)
   Author: hojin <aporlo22@gmail.com>
   Date:   Tue May 21 17:13:51 2019 +0900
   
       190521|git-hub특강 1
   
   ```

   - 현재까지 커밋된 이력을 모두 확인할수 있다.

5. git 상태확인하기 

   ```cmd
   $ git status
   ```

   - CLI(Command Line Interface) 에서는 현재 상탤를 알기 위해 반드시 명령어를 통해 확인해야한다
   - 커밋할 목록에 담겨있는지, untracked 인지, commit할 내역이 있는지 등등 다양한 정보를 알려준다.

   





H -1 ) 제목

h - 2 ) 부제목

h - 3 ) 

```python
print('hello')
```

syntex highlighting

screen shot - 가독성 증가 . 편리성 증가

ctrl / : 원본 코드 확인 가능 - typora 기능

ctrl + u : 문장 밑줄치기

`git bash`

[임의사이트명](실제사이트명)

| 표만들기 | 굿   |
| -------- | ---- |
| ctrl + T |      |

 data science - 쥬피터 노트북(머신러닝 딥러닝) | 수식 == markdown 인식가능 

ctrl + , - 화면 글자 크기 증 감소

