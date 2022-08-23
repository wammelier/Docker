# Docker

## Download and install Docker🔗

-   아래으 링크를 탁 들어가서 자신으 OS에 맞게 다운로드를 한다.
    https://docs.docker.com/get-started/

## Start the tutorial

1. termianl(mac) or wsl(window) 창에 아래의 내용 입력 <br/>
   --> $ docker run -d -p 80:80 docker/getting-started
   <br/>
   <br/>

    VMWare 와 Docker 비교  
     ![CreatePlan](./img1.PNG)

<h3>docker 개념정리</h3>
docker hub -> image [pull]
<br/>
image -> container [run]
<br/><br/>

## Docker 명령어

docker pull [imageName] : 도커이미지 다운<br/>
docker images : 도커이미지 목록 보기<br/>
docker run [imageName] : 도커이미지 컨테이너 실행<br/>
docker ps : 현재 실행중인 도커프로세서<br/>
docker ps -a : 실행중이지 않지만 현재 죽어있는 도커 프로세서 보기 (옵션 -a 추가)<br/>
docker stop [imageName] : 컨이테너 중단<br/>
docker start [imageName] : 도커이미지 실행
docker rm : 도커 이미지 삭제<br/>
