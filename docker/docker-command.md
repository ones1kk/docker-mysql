# Docker 명령어

#### Docker는 OS의 자원을 사용하기 때문에 기본적으로 Root 사용자에서 명령어를 사용해야한다. 

#### 자세한 설명은 ```docker --help``` 명령어를 통해 확인하고 현 파일에서는 자주, 유용하게 사용할 명령어를 정리해본다.

## Image 검색

### docker search

> - Docker Hub로부터 사용 가능한 image를 찾는 명령어.
>
> - 공식 이미지는 앞에 사용자의 이름이 붙지 않는다.

### docker pull

> - Docker Hub로부터 image를 다운받는 명령어.

### docker images

> - 현재 Host PC에 다운 받아져 있는 image들을 출력하는 명령어.

### docker run

> - docker run <옵션><이미지이름 or 이미지ID><실행할 파일>
> - 다운받은 image를 실행하는 형태인 컨테이너로 만드는 명령어다.₩
> - 파일이 종료되면 컨테이너도 같이 종료된다.
> - 컨테이너를 계속 유지하고싶다면 --detach 옵션을 이용한다.
> - --interactive, --tty 옵션을 통해서  Interactive Terminal Mode로 컨테이너 실행 후 컨테이너 내부 bash shell로 접속할 수 있다.

### docker ps

> - 실행 중인 컨테이너 목록을 확인한다.
> - --all 옵션을 통해 이전에 종료되었던 컨테이너들을 포함한 모든 컨테이너 목록을 확인할 수 있다.


