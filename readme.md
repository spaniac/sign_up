# Django 프로젝트 생성
1. 가상환경 설정(pyenv, pyenv-virtualenv)
    pyenv-virtualenv로 가상환경 생성 후 pyenv local (가상환경명)을 등록해주면 터미널에서 폴더 접근 시 자동으로 가상환경을 활성화한다.

2. 가상환경 내에서 django 설치 및 django-admin 명령어로 프로젝트, 앱 생성
    설정파일 폴더는 config로 리네임.

3. mysqlclient(mysql connector driver) 설치(pip)
    .zshrc 파일에 export PATH=$PATH:/usr/local/mysql/bin 추가
    추가 전 실제 저 경로에 mysql이 설치되어 있는지 확인
    mysql 미설치 또는 경로가 설정되어있지 않으면 mysql_config_path 에러가 발생.