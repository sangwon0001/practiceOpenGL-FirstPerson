# practice-FirstPersonOpenGL


## 개요
　제가 혼자서 OpenGL을 공부하며 만든 간단한 3D FPS 렌더링 프로그램입니다.
이 프로그램에서 할 수 있는 거라곤 단순히 WASD키로 돌아다니기, 마우스로 시점 조작하기, 상자에 부딪치기 정도 뿐입니다.
하지만 렌더링과 관련해서는, OpenGL과 쉐이딩 언어 GLSL을 이용하여 조명, 그림자, Blender에서 exported된 모델 불러오기 등 괜찮은 기능들이 구현돼 있습니다.

## 코드를 읽어보시려는 분께
　제 첫 3D 렌더링 프로그램이기도 하고, 새로 배운 대로 그때그때 추가하느라 코드가 깔끔하지 않고 알아보기도 힘들어졌습니다.
게다가 주석도 거의 안 달려 있습니다 죄송합니다. ㅜㅜ
혹시나 제 코드를 읽으며 대체로 이해가 되는데, 한 부분이 이해가 안 되신다면 제 이메일로(woos8899@gmail.com) 질문 보내주세요.
하나도 모르겠는데 OpenGL을 배워보고 싶다 하시는 분은, [제가 OpenGL을 배운 웹사이트](https://learnopengl.com/) 를 방문해 보시길 추천해 드립니다.
물론 영어입니다.

## 코드를 실행하시려는 분께
　firstPersonPractice 폴더 안의 내용물들이 Github에 있는 그대로 모두 필요합니다.
깃허브로 다운로드하는 것이 번거로우시다면 [구글 드라이브](https://drive.google.com/file/d/0BzF0hEIffU-tNnFfM1k1S2x6ek0/view?usp=sharing)에서 zip 파일을 다운로드하실 수 있습니다.
압축을 푼 뒤 src 폴더 안에 가시면 소스 파일들이 있습니다. 그 안에서 "main_v2.py"를 실행해 주세요.

## 실행환경 준비가 번거로우신 분께...
　위의 구글 드라이브 링크에서 zip 파일 안 exe 폴더 안에 Pyinstaller로 빌드된 exe 파일이 있습니다.
"main_v2.exe" 파일을 실행해 주세요.
이를 이용하시면 Python이 설치돼 있지 않더라고 실행할 수 있을 것입니다. (테스트 해보진 않았습니다.)

## 실행환경

#### 파이썬 버전

　Python 3.5

#### 필요 라이브러리
　Numpy

　PyGame

　PyOpenGL

　Pillow

## 조작법

　WASD : 이동

　↑←↓→ : 시점 조작

　SPACE : 비행 모드 켜진 경우 수직 상승

　SHIFT : 비행 모드 켜진 경우 수직 하강

　F : 손전등 켜기/끄기

　F6 : '마우스로 시점' 조작 켜기/끄기 (기본값 꺼짐)

　F7 : '비행 모드' 켜기/끄기 (기본값 꺼짐)

　F8 : 배경 모델 불러오기 (몇 초 간 프로그램이 멈춤)

　F9 : '그림자 방향을 시점과 동일화' 켜기/끄기 (기본값 꺼짐)

　F10 : 상자들 회전 속도 10 줄이기 (기본값 20)

　F11 : 상자들 회전 속도 10 늘이기

　ESC : 프로그램 종료
