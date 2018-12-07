## TensorFlow의 설치 및 기본적인 Operations.md
> <a href="https://www.youtube.com/watch?v=-57Ne86Ia8w&index=3&list=PLlMkM4tgfjnLSOjrEJN31gZATbcj_MpUm">참고</a>

<br>
윈도우는 python 3.5 버전 (64bit) 에서만 다운로드 가능하다고 합니다..
그 위의 버젼들에서는 <br>

```
Could not find a version that satisfies the requirement tensorflow (from versions: )
No matching distribution found for tensorflow
```
<br>
라는 에러를 뱉습니다..

<br>
하지만 우리에게는 docker가 있습니다!!

<br>
docker를 통해 tensorflow를 설치하는 방법은 아래와 같습니다.

<br>
참고: https://www.tensorflow.org/install/?hl=ko

```
$ docker pull tensorflow/tensorflow                  # docker hub에서 tensorflow의 latest image를 pull
$ docker run -it -p 8888:8888 tensorflow/tensorflow  # 로컬호스트의 8888번 포트로 tensorflow 이미지를 run (Jupyter notebook server)
```

<br>
자 이제 브라우저를 열어 localhost:8888으로 접속하면..

<br>
아래와 같이 tensorflow이미지의 Jupyter notebook server 화면이 보입니다!

<br>

<a target="_black" href="http://cyan91.tistory.com/7">Jupyter notebook server란?</a>

<br>

![2018-12-07 1 54 20](https://user-images.githubusercontent.com/26675063/49628490-b0b32880-fa27-11e8-9ec7-0a4cd1b401aa.png)

