# 0327 Git, Github, Django
- Git: 하나의 파일에 수정사항을 계속 반영해주는 시스템
- Github: 자신의 프로젝트를 업로드하고 다른 사람과 협업

# Git 명령어 정리
> git init: 해당 폴더오 깃허브 연동
> git remote add origin 주소: 해당 Repository 주소 복사해서 넣기
> git remote -v: 연동 확인
> git branch -M main: 브랜치 이름 main으로 바꾸는 것
> git pull origin main: main branch의 최신사항 반영
> git add .: .은 해당 경로의 모든 파일
> git commit -m "커밋 메시지": github에 기록할 내용
> git push origin main: origin의 main에 기록,수정사항을 올리는 것

# Git Branch 명령어 정리
> git branch: branch 목록 확인
> git branch "브랜치이름": 새 브랜치 생성
> git switch "브랜치이름": 브랜치 이동
> git branch -d "브랜치이름": 브랜치 삭제 