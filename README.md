# iot-mfc-2026

IoT반 MS MFC 학습 리포지토리


## MFC?

Microsoft Foundation Class 의 약자. C++ 기반의 윈도우 프로그래밍 라이브러리 중 하나

GUI를 디자인, 실행하는 앱을 만들기 위해서 MS에서 만든 기술

- Linux : Qt, GTK, wxWidgets ....
- Windows : Qt, Win32API, ...

리눅스와 윈도우가 OS기반이 다르기때문에 초기에 표준화를 못함. Win32API 기반으로 GUI를 라이브러리화 -> MFC

윈도우에서만 동작하는 GUI 라이브러리 프레임워크임.

현재는 리룩스에서 Wine 에뮬레이터로 Windows 기반 GUI도 실행 가능(PC카톡 윈도우 버전)


### MFC 단점 및 장점

#### 단점

- 너무 어렵다. 최소 6개월은 공부를 해야하는 문제
- 오래된 기술로 생각보다 최신 튜토리얼이 별로 없음.
- 기업이 예전부터 사용하던 솔루션 기반이 변경하기 힘들어서 계속 사용

#### 장점

- C++ 자체가 어려운데 MFC를 사용하면 복잡한 Win32 API를 직접 다루지 않아도 구현이 가능
- 생산성 향상 : 기존 C/C++ 대비하여 생산성 높다는 의미. C#, Java등 OOP와는 비교하면 안됨
- C++ 실력이 많이 좋아짐


### MFC 학습 링크

- Microsoft Learn :



## MFC 튜토리얼

### 순수 Win32 API로 윈도우 만들기

- 중요! Windows 32 bit에서 C++에 있는 여러 기능을 손쉽게 쓰도록 만들어높은 API(Application Programming Interface)
- 최초에는 이를 통해서 윈도우를 직접 개발


#### Visual Studio 실행
