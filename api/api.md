# API
## 로그인

| 항목           | 내용                                     |
| ------------ | -------------------------------------- |
| URL          | `/login`                               |
| Method       | `POST`                                 |
| Request Body | `id`: string, `password`: string       |
| Response     | `message`: string, `jwt token`: cookie |

---

## Home

| 항목       | 내용                                     |
| -------- | -------------------------------------- |
| URL      | `/home`                                |
| Method   | `GET`                                  |
| Response | `best`: single data, `trending`: array |

---

## 지도 검색

| 항목       | 내용              |
| -------- | --------------- |
| URL      | `/map`          |
| Method   | `GET`           |
| Response | `result`: array |

---

## 해설 검색

| 항목                       | 내용                                                                     |
| ------------------------ | ---------------------------------------------------------------------- |
| URL                      | `/explanation/search?all=false&difficulty=blue&color=yellow&type=dino` |
| Method                   | `GET`                                                                  |
| Request Query Parameters | `all`: boolean, `difficulty`: string, `color`: string, `type`: string  |
| Response                 | `result`: array                                                        |

---

## 해설 쓰기

| 항목           | 내용                                                                                 |
| ------------ | ---------------------------------------------------------------------------------- |
| URL          | `/explanation/write?difficulty=blue&color=green&type=tohook`                       |
| Method       | `POST`                                                                             |
| Request Body | `difficulty`: string, `color`: string, `type`: string, `video`: string (풀이 영상 URL) |
| Response     | `message`: string                                                                  |

## 추가로 필요한 UI
- 해설을 클릭해서 들어갔을 때 detail 화면 
- 좋아요 기능
## 나중에 추가하면 좋을 것 같은 UI
- 마이페이지
- 즐겨찾기 기능

의문
- app에서 페이징은 어떻게 구현되는가

---

# Data
## 사용자 정보

| 속성 이름     | 타입     |
| --------- | ------ |
| id        | number |
| name      | string |
| email     | string |
| createdAt | Date   |


## 해설 - 검색 창에 띄울 때

| 속성 이름     | 타입     |
| --------- | ------ |
| id        | number |
| name      | string |
| gym       | string |
| image     | url    |
| createdAt | Date   |

## 해설 - 눌러서 들어갔을 때

| 속성 이름        | 타입     |
| ------------ | ------ |
| id           | number |
| name         | string |
| gym          | string |
| image        | url    |
| createdAt    | Date   |
| like         | number |
| video        | url    |
| descriptions | string |


