## 블로그를 위해 꼭 알아야 하는 폴더, 파일 구조
- `_posts` : 글을 마크다운으로 작성해서 저장하는 폴더
- `about.md` : About 페이지에서 나타날 내용
- `_featured_categories` : 카테고리 (홈페이지 상의 왼쪽에 노출되는 큰 메뉴)
- `_featured_tags` : 카테고리의 태그(큰 메뉴의 소제목)
- favicon.ico : 파비콘 아이콘
- `_config.yml` : 기본 설정 파일
- `_data` : 유저 데이터가 저장된 폴더로 author.yml만 수정하면 됨
- `tile-wide.png`, `tile.png` : 홈페이지의 좌측 배경 이미지




### Structure
```
├── README.md
├── _config.yml : 기본 설정이 저장된 파일
├── _data : 유저 데이터가 저장된 폴더, author.yml만 수정하면 됨
├── _draft : 초안 작성 폴더, 커밋해도 반영되지 않음
├── _featured_categories : 카테고리(메뉴판의 큰 제목)
├── _featured_tags : 카테고리의 태그(메뉴판의 소제목)
├── _includes : 기본 홈페이지 포맷
├── _ipynbs : ipynb 저장 폴더
├── _js : 자바스크립트 소스 저장 폴더
├── _layouts : 타입별 레이아웃 폴더
├── _plugins : 플러그인 저장 폴더. 그러나 Github에서 빌드시 플러그인 사용 불가능
├── _posts : 글 저장 폴더
├── _sass
├── _site : 빌드시 생기는 폴더, 신경쓸 필요 없음
├── about.md : about에서 나타날 내용
├── assets : css, js, img 등 저장하는 폴더
├── favicon.ico : favicon 아이콘
├── feed.xml
├── index.html
├── robots.xml
├── search.html
├── sitemap.xml
├── tile-wide.png
└── tile.png
```

- ```_config.yml```, ```_data```, ```_featured_categories```, ```_featured_tags```, ```about.md``` 내용 수정
- ```favicon.ico```, ```tile-wide.png```, ```tile.png``` 원하는 이미지로 설정


### 원격 빌드
- Github 저장소에 Push하면 Github Action이 빌드

### 글 작성
- ```_featured_categories```, ```_featured_tags```에 각각을 추가한 후, ```_posts```에 글을 작성
- 글 제목 형태는 ```2018-01-03-title1.md``` 이런 방식처럼 작성! 날짜를 빼고 쓰면 반영되지 않음

