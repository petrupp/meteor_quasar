## meteor + quasar 설치

### 1.글로벌 meteor 설치
- linux
`curl https://install.meteor.com/ | sh`
- window
`npm install -g meteor`

### 2.공식 퀘이사 클론
- 참조 소스
`git clone https://github.com/quasarframework/quasar-template-meteor.git`

- install
`meteor npm install`

- linux link
`ln -s ../node_modules/@quasar/extras/material-icons/web-font public`

- window link
`mklink /D "public\web-font" "..\node_modules\@quasar\extras\material-icons\web-font"`

- run
`meteor`