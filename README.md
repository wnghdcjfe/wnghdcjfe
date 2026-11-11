
```
입력: $ARGUMENTS

입력의 첫 단어가 하위 명령이고, 나머지가 주제다. 하위 명령이 없거나 아래 목록에 없으면 아무 작업도 하지 말고 사용법(`/yt-mini discover 주제`)만 안내한다.

## discover

1. 주제로 웹 검색을 3회 이상 한다. 검색 대상을 youtube.com 도메인으로 제한하고, 한국어와 영어 검색어를 섞는다.
2. 검색 결과에서 실제 유튜브 영상 또는 채널을 최대 8개 고른다. 주소가 youtube.com 또는 youtu.be 인 것만 넣는다.
3. 아래 열을 가진 표로 정리한다: 제목 / 채널 / 주소 / 어떤 내용인지 한 줄.
4. 조회수, 업로드 날짜, 구독자 수는 검색 결과에 명시된 경우에만 적고, 없으면 "확인 안 됨"이라고 쓴다. 추측해서 채우지 않는다.
5. 표 아래에 "아직 덜 다뤄진 각도" 3개와 그 근거, 각 각도에 맞는 영상 제목 후보를 2개씩 쓴다.
6. 결과를 `ideas/오늘날짜-주제.md` 파일로 저장한다. 날짜는 YYYY-MM-DD 형식. `ideas` 폴더가 없으면 만든다.
7. 마지막에 저장 경로와, 사람이 직접 확인해야 할 항목을 알려준다.

```
#### Introduce
 - AVISS CTO & CEO [AVISS](https://aviss.kr/main/main.php) 
 - Former)NAVER DEVELOPER
 - [![Youtube Badge](https://img.shields.io/badge/YouTube-red?style=for-the-badge&logo=youtube&logoColor=white)](https://www.youtube.com/channel/UCoN1XLeAX2OazuZdQ9b8U9Q)    

#### Lecture
- [10주 완성 C++ 코딩테스트 / 인프런](https://inf.run/xZhA)
- [CS지식의 정석 / 인프런](https://inf.run/17Fb)


#### Publication
- 면접을 위한 CS전공지식노트 / 길벗 / 2022 [[Yes24](https://www.yes24.com/Product/Goods/108887922)] / 1위
- 실시간 모니터링 시스템을 만들며 정복하는 MEVN / 비제이퍼블릭 / 2021 [[Yes24](https://www.yes24.com/Product/Goods/104208010)] / 63위

#### Profile Link
https://blog.naver.com/jhc9639/222633934401
