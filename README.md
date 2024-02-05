## 깃허브 프로젝트 연습

![image](https://github.com/SSGView/SSGBoardProject/assets/159003240/a43d44b4-f2b2-49f4-88f6-d48632425922)
- 로컬 깃을 만들자
<br><br><br>
![image](https://github.com/SSGView/SSGBoardProject/assets/159003240/83a46a50-a9ea-4410-bbdb-9317ea7010cd)
- 원격 깃을 연결 (링크는 아래 사진에서 찾을 수 있다 )
<br><br><br>
![image](https://github.com/SSGView/SSGBoardProject/assets/159003240/ba3ed13a-6038-4068-858d-0f3d2c57d1e6)
<br><br><br>

![image](https://github.com/SSGView/SSGBoardProject/assets/159003240/2c97be2a-c864-4d47-b470-8e1e4a727f26)
- git pull 명령을 하면 원격 깃허브의 데이터가 내 로컬로 땡겨진다
<br><br><br>
## 주의 !!!
- 로컷 깃을 다 날리고, 깃허브 코드대로 하고싶다면 git clone 을 하도록!



<br><br><br><br>
# 나만의 브랜치를 만들어서 코드를 짜자!

![image](https://github.com/SSGView/SSGBoardProject/assets/159003240/249008c9-a5c7-41c8-bfcb-3cd21030fd93)

<br><br><br><br>

### 브랜치 생성
$ git branch <branch 이름>

### 브랜치 이동
$ git checkout <branch 이름>

### 브랜치 생성후 이동 (단축 명령어)
$ git checkout -b <branch 이름>


# 내가 할 일을 알리자! 이슈

![image](https://github.com/SSGView/SSGBoardProject/assets/159003240/afc607cb-8515-45b9-ab37-5b1e141ea841)
<br><br><br><br><br><br>
### 1. Issues 에 이슈를 주어진 템플릿에 작성 (#숫자 안써도 된다)
<br><br>
![image](https://github.com/SSGView/SSGBoardProject/assets/159003240/224fd070-0120-4a72-8216-a8f209d59bee)

![image](https://github.com/SSGView/SSGBoardProject/assets/159003240/f0c907fa-490b-45d0-8abb-cb8bb8a828bc)

<br><br><br><br><br><br>
### 2. commit을 push 후, pull request 에 이슈와 동일한 #숫자 로 제목 쓸 것
<br><br>
![image](https://github.com/SSGView/SSGBoardProject/assets/159003240/9c41f042-4c82-46a2-a416-fcbf2c35375a)
<br><br>
![image](https://github.com/SSGView/SSGBoardProject/assets/159003240/da93a9f2-9a1d-4739-a271-84b50aaa4dd3)
<br><br>
## push를 하기전에 git pull 을 해둔다 !!!! (내가 push 하는 사이에 누군가 코드 수정을 했을 확률이 있기 때문이다.)
- push 를 한다! (나의 브랜치명을 써야 하는거 잘 확인.) 
<br><br><br><br><br><br>

<br><br>
![image](https://github.com/SSGView/SSGBoardProject/assets/159003240/fef708be-ab48-4cd4-9798-02397b3be478)
- 오.... pullrequest 할거냐고 묻는다.

<br><br>
![image](https://github.com/SSGView/SSGBoardProject/assets/159003240/f8445654-5a61-47a9-8198-eb4896235af9)
- 주의!!!! 내 branch 선택해야 PR 할거냐고 묻는다!

<br><br>
![image](https://github.com/SSGView/SSGBoardProject/assets/159003240/ae32ff41-edaa-4a5f-8729-5c98f2a637bf)
<br><br><br><br><br><br>
### 4. 그 후에 merge 같은걸 누르지 말고 기다린다
<br><br>
![image](https://github.com/SSGView/SSGBoardProject/assets/159003240/1fb408ce-bf7d-42fb-a8b5-c1524aaac098)
- 휘제쿤의 comment 귀하군요
- 휘제쿤이 merge를 승인해줬습니다.

<br><br>
![image](https://github.com/SSGView/SSGBoardProject/assets/159003240/736b15f7-8dc3-4221-b03d-01a9c2dc2c7c)

- 우와 이슈 같은 넘버가 업데이트 되었넹
- merge 완료가 되었으면 issue를 close 합니다

<br><br>
![image](https://github.com/SSGView/SSGBoardProject/assets/159003240/0d073254-af23-4c20-80b8-76402bfb3991)

- 우리의 코드는 repo의 좋은 양식이 되었습니다.

<br><br>
### merge가 된걸 쓸거면 pull을 하자!
<br><br>
![image](https://github.com/SSGView/SSGBoardProject/assets/159003240/b388912f-4fd5-4427-add9-de5f028205f1)
- 우선 git checkout main 을 해서 main checkout 상태에서
<br><br>
![image](https://github.com/SSGView/SSGBoardProject/assets/159003240/7f506f2d-c489-4357-8bb6-aa9250b94ebf)
- 다음에 이어서 코드 치기전에는 git pull origin main 을 하자

- 그리고 
  - `git branch -D <제거할 브랜치이름>`  을 통해 branch를 제거하자

    ### 그리고 다시 내 branch를 만들어서 개발을 이어 하자

<br><br>
 <br><br><br><br>




### 제 로컬 git main 이 이상해요!!!
- 천천히 아래 명령문을 하자 (주의 로컬에서 개발 한 후에 하면 다 날라가니 조심)
- git fetch --all
- git reset --hard origin/main
- git pull origin main

### 방금 커밋한거 돌려놓고 싶어요!!!
- git revert HEAD





