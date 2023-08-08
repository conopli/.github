# CONOPLI: 코노플리

<div align="center">
<img src="https://github.com/conopli/.github/assets/77656241/113003a4-f6d1-41fa-8cba-ac960332a54f" />


<br>
<b>당신만을 위한 노래방 플레이리스트!</b>
<br>
</div>
<br>
코노플리는 노래방을 좋아하는 사람들을 위해 개발한 iOS / Android 어플리케이션입니다. 노래방 곡 검색은 물론 개인 플레이리스트 저장, 위치 기반을 통한 주변 코인노래방 검색 등 다양한 기능을 제공합니다. 

- 현재는 TJ만 지원하고 있으며, 추후 KY(금영)도 추가될 예정입니다.
- 1차적인 개발을 마치고 빌드 과정 진행 중에 있으며, 빌드 테스트까지 모두 마치게 되면 추가적인 기능 개발 및 앱 배포단계를 진행할 예정입니다.

## 각 파트별 레포지토리 바로가기
- [Client](https://github.com/conopli/conopli-client)
- [Server](https://github.com/conopli/conopli-web-server)

## 주요 기능 소개

### 나만의 플레이리스트
[나만의-플레이리스트.webm](https://github.com/conopli/.github/assets/77656241/0e27efe6-8562-4943-baf7-9cb16ce66ce7)

검색이나 인기곡 차트에서 찾은 노래를 나만의 플레이리스트로 저장할 수 있습니다. 상황이나 분위기에 따라 이모지, 색깔을 커스텀하여 꾸밀 수 있습니다.  
- 플레이리스트 수정

  [플레이리스트-수정.webm](https://github.com/conopli/.github/assets/77656241/e62344c8-bab3-4c0b-85bb-8bf3ca91d7e1)

  각 플레이리스트를 수정할 수 있습니다. 다른 플레이리스트로 곡을 이동하거나 삭제할 수 있고, 곡의 순서 변경도 가능합니다.

### 인기곡 차트
[인기차트.webm](https://github.com/conopli/.github/assets/77656241/09b1f447-aff0-4c61-8eb2-79cebbef0420)

TJ에 등재된 이 달의 인기곡들을 확인할 수 있습니다. 해당 곡을 터치해 본인의 플레이리스트에 바로 담을 수도 있고, 국가별로 한국 / 팝송 / J-POP의 차트를 각각 제공합니다.

### 내 주변 노래방 찾기
[내-주변-노래방-찾기.webm](https://github.com/conopli/.github/assets/77656241/182c8170-f239-458a-8a83-da85ee05031d)

카카오맵의 JavsScript API를 활용해 기기의 위치 권한을 허용하면 유저의 현재 위치를 기반으로 1km 이내의 노래방 위치를 확인할 수 있습니다.

### 노래방 곡 검색
[노래방-곡-검색.webm](https://github.com/conopli/.github/assets/77656241/18457255-bbca-4908-bf0a-2022fe6d5f3d)

현재 TJ에 등재된 노래방 곡을 검색할 수 있습니다. 국가별 검색을 지원합니다.

## 참여 팀원
|             **신승구<br>FE**            |               **김민경<br>FE**              |             **이수영<br>BE**             |
|:------------------------------------------:|:-----------------------------------------:|:------------------------------------------:|
| photo:ninefloor                            | photo:jade                                | photo:sooyoung                             |
| [@ninefloor](https://github.com/ninefloor) | [@ansmeer](https://github.com/ansmeer008) | [@sussa3007](https://github.com/sussa3007) |

## 기술 스택

### FrontEnd

<img src="https://img.shields.io/badge/react native-61DAFB?style=for-the-badge&logo=react&logoColor=black"> <img src="https://img.shields.io/badge/expo-000020?style=for-the-badge&logo=expo&logoColor=white"> <img src="https://img.shields.io/badge/react navigation-8c90e0?style=for-the-badge"> <img src="https://img.shields.io/badge/recoil-3578e5.svg?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIGZpbGw9Im5vbmUiIHdpZHRoPSIyMzY4IiB2aWV3Qm94PSIzMCAxMSAyNy41IDc4Ij48Y2lyY2xlIGN4PSI0My41IiBjeT0iMTguNSIgZmlsbD0iI2ZmZiIgcj0iNy41Ii8+PGNpcmNsZSBjeD0iNDMuNSIgY3k9IjgxLjUiIGZpbGw9IiNmZmYiIHI9IjcuNSIvPjxnIHN0cm9rZT0iI2ZmZiIgc3Ryb2tlLXdpZHRoPSIzIj48cGF0aCBkPSJNNDMuOTk5IDI1QzQyLjUgMzcgNTcuNSAzNCA1Ny41IDQyLjVjMCA1LTUuODc4IDYuMzY1LTEzLjUwMSA3QzM3Ljk5OSA1MCAzMCA1MCAzMCA1OHMxNiA1LjUgMTMuOTk5IDE3TTM0LjEzMiAzMy4zNTNjMCAxNS4yODkgMjMuMTUgMTguMjg5IDIzLjE1IDMyLjYyIi8+PC9nPjwvc3ZnPg==&logoColor=white"> <img src="https://img.shields.io/badge/css-1572B6?style=for-the-badge&logo=css3&logoColor=white"> <img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"> <img src="https://img.shields.io/badge/figma-F24E1E?style=for-the-badge&logo=Figma&logoColor=white">
<img src="https://img.shields.io/badge/eslint-4B32C3?style=for-the-badge&logo=ESLint&logoColor=white"> <img src="https://img.shields.io/badge/stylelint-263238?style=for-the-badge&logo=stylelint&logoColor=white"> <img src="https://img.shields.io/badge/prettier-F7B93E?style=for-the-badge&logo=Prettier&logoColor=black"> 

### Backend


### Team Tools

<img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white"> <img src="https://img.shields.io/badge/git-F05032?style=for-the-badge&logo=git&logoColor=white"> <img src="https://img.shields.io/badge/notion-000000?style=for-the-badge&logo=notion&logoColor=white"> <img src="https://img.shields.io/badge/discord-5865F2?style=for-the-badge&logo=discord&logoColor=white">

