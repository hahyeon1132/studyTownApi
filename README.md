# StudyTownApi
스터디 타운 api
### [개발자 환경 설정]
1. vscode에 Remote Development, Docker 확장 설치

2. Docker Image 생성: ./create_node_image.sh
   
3. 컨테이너 실행: ./run_dev_docker.sh [컨테이너 이름]
   예) ./run_dev_docker.sh studytown-api
   확인) docker ps -a | grep studytown-api

4. VSCode 실행 후 좌측 최하단 모서리의 "원격 창 열기"(녹색 버튼) 클릭 
   -> "Attach to Running Container..." 선택
   -> 목록에서 "2." 에서 지정한 "컨테이너 이름" 선택

5. 파일 > 열기 선택
   경로 예 "/api" 입력 후 확인