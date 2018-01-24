# 들어가며

요즘에는 전자 장치를 모바일 앱을 통해 **블루투스**로 제어하는 것이 기본 기능이 되었습니다.

저 또한 관련 기술을 익히기 위해, 근거리 무선 통신용 반도체 제품군으로 유명한 노르딕 반도체\(Nordic Semi\)의 개발용 제품인** nRF52832 DK 보드**를 사용하여 블루투스 관련 어플리케이션의 개발에 대해 학습하는 것을 적극 검토하게 되었습니다.

![](/images/nRF52_DK_v1.1.0_Kit_content.png)

이 글은 그 초기 과정에 있어 많은 참고가 되는 영문 매뉴얼인 [Development with GCC and Eclipse \(GCC와 이클립스를 이용한 nRF 개발\)](https://devzone.nordicsemi.com/tutorials/7/development-with-gcc-and-eclipse/)를 참조하여 작성 되었으며, 한글화 외에도 현재 상황에 맞춰 업데이트 된 내용을 공유하고자 작성 하였습니다.

본 매뉴얼의 목표는:

* 관련 파일들의 설치와 설정
* 터미널에서 예제 컴파일 해 보기
* 프로젝트에 필요한 최소한의 파일을 통해 전용 프로젝트 생성 해 보기 
* 이클립스에서 전용 프로젝트를 들여오고, 컴파일 및 디버깅 해 보기 

입니다.

이러한 내용이 유사한 작업을 개시하고자 하는 모바일 개발자 분들과 전자 엔지니어 분들께 작은 도움 되길 바라봅니다.

\(많은 개발자분들이 윈도우즈 환경에서 작업하시는 것을 고려하여, 여기서는 Windows 10 기반으로 설명하고 있는 점 양해 바랍니다.\)

# 작성자

김성준

* 프로필: [bus710.net](http://bus710.net)  
* 연락처: [bus710@gmail.com](mailto:<bus710@gmail.com)

## Change Log

* 0.0.2 \(2017/10/10\)
  *  부록 2 \(예제 BLE 프로젝트의 소스코드 분석\) 시작
* 0.0.1 \(2017/09/30\)
  * 초기 버전. 기본 설치 및 설정에 주력.



