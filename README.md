# TASK-FORCE

# 💻 기술스택
- APP : react native
- Server : nestJS
  
# 📖 Rule
- 회의시간 : `매주 목요일 12:00`
- 회의장소 : `discord`
- 진행사항은 github issue와 projects로 공유하기
- 호칭은 ${이름}님으로 하기

# 🙋‍♂️ 요구사항
## 사용자
### 로그인
1. 사용자는 네이버 로그인을 통하여 로그인 할 수 있다.
2. 로그인한 사용자는 아래와 같은 기능을 사용할 수 있다.
  - 해설작성
  - 댓글
  - 팔로우
  - 좋아요
  - DM

## 해설
1. 사용자가 해설 작성 버튼을 누른다.
2. 사용자가 클라이밍장, 문제 난이도, 홀드 색깔을 선택한다.
3. 사용자가 영상을 업로드한다.
4. (optional) 사용자가 크럭스 설명을 작성한다.
5. 사용자가 작성완료 버튼을 누른다.

### 추후에 추가하면 좋을 것
1. 사용자에게 비슷한 문제들을 보여주기
2. 돌간의 각도와 거리를 잘계산하면 ai를 안써도 되지 않을까..?

## 클라이밍장
1. 각 클라이밍장은 지도에 표시된다.
2. 사용자는 클라이밍장을 선택하여 해당 클라이밍장의 해설들을 볼 수 있다.

## 댓글
1. 사용자는 다른 사용자의 해설에 댓글을 달 수 있다.

## 좋아요
1. 사용자는 다른 사용자의 해설, 댓글, 게시글에 좋아요를 할 수 있다.
2. 사용자는 좋아요한 해설들을 마이페이지에서 모아볼 수 있다.

## DM
1. 사용자가 다른 사용자의 프로필을 누르면 DM 버튼이 나타난다.
2. 사용자는 DM 버튼을 눌러 다른 사용자와 DM을 시작한다.

## 커뮤니티
1. 사용자는 커뮤니티에 게시글을 작성할 수 있다.

## 팔로우
1. 사용자는 다른 사용자를 팔로우 할 수 있다.
2. 팔로우한 사용자가 해설을 작성하면 알림이 온다.

# 🛠️ 설계
## UI
[figma link](https://www.figma.com/file/wlnfCdBN9G9yu9J7E8aZNn/App-UI?type=design&node-id=0%3A1&mode=design&t=1l3IgGCmiSLPYbbU-1)
## ERD
## Infra
## API DOCS

# 🧑‍🤝‍🧑 Git Convention
[Udacity Style translate](https://github.com/gyoogle/tech-interview-for-developer/blob/master/ETC/Git%20Commit%20Message%20Convention.md)
