# Package Manager

![chocolatey](https://user-images.githubusercontent.com/114221785/230291182-c80ce0e6-246e-4aa7-85ea-71532b5f6452.png)
##
### Chocolatey
#### - Windows 사용자를 위한 패키지 매니저
#### - 프로그램(패키지)의 설치, 업데이트, 삭제가 매우 쉽다
#### - Microsoft에서 개발 -> 신뢰
##


### 1. 프로그램 설치를 간단한 커맨드로 할 수 있다.
```
choco install bandizip
```
- 해당 프로그램의 사이트에 들어가서 다운로드를 하는 방식보다 명령어 한 줄로 상당히 간편하게 설치할 수 있다.


### 2. 설치한 프로그램의 목록을 볼 수 있다.
```
choco list --localonly
```
![스크린샷 2023-04-06 오후 3 50 01](https://user-images.githubusercontent.com/114221785/230294104-7dbf5917-2dff-4138-b2ac-e1f292386232.png)
- choco install 명령어로 어떤 패키지를 설치했는지 목록을 볼 수 있다.


### 3. 프로그램 최신 버전 업데이트를 간단한 커맨드로 할 수 있다.
```
choco upgrade bandizip
```


### 4. 프로그램 삭제도 매우 간편하게 할 수 있다.
```
choco uninstall bandizip
```
- 제어판에서 일일히 프로그램을 삭제하는 방식보다 간단한 명령어 한 줄로 삭제할 수 있다.
- choco list 명령어로 설치된 패키지 목록을 보고 삭제하고 싶은 패키지가 있으면 choco uninstall <package>하면 삭제가 된다.

##


### 6000개가 넘는 windows 소프트웨어 관리
- bandizip, git, python, node.js, chrome, visual studio code, notepad++, jdk, intelliJ... 개발할 때 많이 사용하는 소프트웨어를 터미널 환경에서 패키지 매니저를 통해 관리를 매우 편하게 할 수 있다.

##

### windows package manager
#### - chocolatey
#### - winget
#### - scoop

##

### Homebrew package manager for mac os
#### 1. install
```
brew install node
```
#### 2. package list
```
brew list
```
![스크린샷 2023-04-06 오후 4 13 29](https://user-images.githubusercontent.com/114221785/230302086-f3a7bcf4-d612-4176-913a-00031ce865e0.png)

#### 3. upgrade
```
brew upgrade node
```

#### 4. uninstall
```
brew uninstall node
```

##
### windows에서 chocolatey 설치방법

#### 1. <a href="https://chocolatey.org/">Chocolatey 공식사이트</a>에 접속한다.
![스크린샷 2023-04-06 오후 4 29 24](https://user-images.githubusercontent.com/114221785/230305743-8687bdb8-ae8e-4267-bebd-55a019862fc9.png)
#### 우측 상단에 Try It을 클릭한다.
![스크린샷 2023-04-06 오후 4 31 46](https://user-images.githubusercontent.com/114221785/230306507-c46f34f5-45ac-4f89-8880-ac12d535a5a2.png)
#### chocolatey 설치 커맨드를 복사한다.

#### 2. 윈도우 검색 창에 Windows PowerShell을 검색하여 관리자 권한으로 실행합니다. 패키지 매니저로 프로그램 설치 밎 삭제 시 관리자 권한이 필요하기 때문이다.
![스크린샷 2023-04-06 오후 4 25 32](https://user-images.githubusercontent.com/114221785/230304879-ab3d6b76-24f2-4a03-b17c-3775daa60250.png)
#### 아까 복사한 커맨드를 붙여 넣는다.
![스크린샷 2023-04-06 오후 4 34 30](https://user-images.githubusercontent.com/114221785/230306851-722070b6-6d60-4a5e-8e43-cef7f1782a76.png)

### 패키지 매니저를 설치 완료하면 한 번 써보세요!
#### 구글 크롬을 다운로드 해봅시다.
![스크린샷 2023-04-06 오후 4 37 13](https://user-images.githubusercontent.com/114221785/230307461-13d7ebb4-1765-48e2-9d61-6710862ceff2.png)

![스크린샷 2023-04-06 오후 4 37 58](https://user-images.githubusercontent.com/114221785/230307620-c57f4be5-b573-4bda-9b19-4d4f984f70a4.png)

![스크린샷 2023-04-06 오후 4 38 39](https://user-images.githubusercontent.com/114221785/230307831-64edbeb5-7c9f-4687-ad1b-ccc773df7058.png)

### 내가 원하는 프로그램을 다운로드 하는 방법
#### 패키지 이름을 모르겠다면 인터넷에 choco install <내가 원하는 프로그램>을 검색하여 명령어가 어떻게 되는지 보고 copy & paste하여 간단하게 프로그램 설치를 할 수 있습니다. 앞으로 모든 프로그램을 패키지 매니저를 통해 관리해보세요
![스크린샷 2023-04-06 오후 4 38 39](https://user-images.githubusercontent.com/114221785/230307831-64edbeb5-7c9f-4687-ad1b-ccc773df7058.png)프로그램
![스크린샷 2023-04-06 오후 4 38 39](https://user-images.githubusercontent.com/114221785/230307831-64edbeb5-7c9f-4687-ad1b-ccc773df7058.png)
