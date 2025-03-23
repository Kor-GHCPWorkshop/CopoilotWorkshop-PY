# GitHub Copilot Workshop
안녕하세요. GitHub Copilot Workshop 리포지토리 입니다. 
이 Repository는 여러개의 다른 실습 과제들을 담고 있으며, GitHub Copilot의 기본적인 코드를 제안받는 사용법 부터 추가적인 다른 워크플로우에 이용할 수 있는 방법까지 핸즈온 경험을 기반으로 한 워크샾 내용을 담고 있습니다. 
각 프로젝트는 GitHub Copilot의 서로 다른 사용례를 담고 있으며, 개별적인 실습 과제로서 마무리 됩니다.

## 실습 환경
- VS Code 또는 Codespaces를 활용합니다.
  * 다른 IDE도구 (IntelliJ IDEA, Android Studio등)에서, VS Code와 기능적인 차이가 있을 수 있어, 지원되지 않는 실습예가 있을 수 있습니다.
- GitHub Copilot 플러그인을 설치하고, GitHub Copilot Business 라이센스가 있는 계정으로 로그인하여 사용할 수 있는 상태여야 합니다.
- VS Code 및 GitHub Copilot 플러그인은 **최신 버전으로 업데이트 되어 있어야 합니다.**

  ### 언어 및 빌드
  (* 실제 환경까지 모두 셋업이 어려운 경우, 사용법과 코드를 제안받는 것에 목적을 두고 실습)
  - Python: 3.x, VS Code의 Python language pack
  - Javascript, React

## GitHub Copilot의 기본

## Task 1: 간단한 함수 및 테스트 코드 제안 받기 (코드완성)
 - GitHub Copilot를 활용하여 간단한 함수와 테스트 코드를 제안받는 실습입니다. 이를 통해 기본적인 Copilot의 기능을 활용하는 방법을 익힙니다. 
 - GitHub Copilot Log를 확인하여, 오픈소스와 매치되는 코드인 경우 레퍼런스 정보를 확인합니다. 
 - VS Code의 Copilot 메뉴에 관한 기본적인 설정들을 변경해 봅니다. 

## Task 2: 가위, 바위, 보 게임 만들기 (Copilot Chat사용용)
 - GitHub Copilot과 함께 가위, 바위, 보 게임을 만들어 봅니다.
 - 추가적인 스팍, 도마뱁을 가위, 바위, 보 게임에 추가해 봅니다. 
 - Copilot을 통해 테스트 코드를 작성해 봅니다.
 - Copilot chat의 각종 메뉴들을 사용해 봅니다.
 - Copilot Code Review를 통해, 코드에 대한 리뷰를 받아 봅니다.
 - Commit message 자동 생성 기능을 사용해 보고, Custom instruction을 제공하여, 원하는 형태로 commit message를 제안받아 봅니다.

## Task 3: Django 웹앱 만들기 & Copilot에게 Custom instruction 제공하기
  - Copilot Edit을 활용해 Django를 이용하여 간단한 웹앱을 만들어 봅니다.
  - Copilot에게 Custom instruction을 제공하여, 원하는 형태로 코드 제안을 받아 봅니다.
  - 웹앱에 대한 다양한 CSS 스타일을 제안받아 봅니다.
  - 웹앱에 대한 테스트 코드를 작성해 봅니다. 
  - 웹앱을 Azure Kubernetes로 배포하는 GitHub Actions 워크플로우를 제안받아 봅니다.

## Task 4: 코드 내 문제점을 찾고 해결 방법 제안 받기 (추가 컨텍스트 제공공)
  - 코드에서 Copilot을 트러블 슈팅이나 보안 문제점 해결에 이용해 봅니다.  
  - @workspace, #file, #selection, #terminalSelection등 다양한 방법으로 추가적인 문맥정보를 제공하는 방법을 실습합니다. 

## Task 5: 코드 리팩토링
  - 코드 블럭을 Copilot을 활용하여 리팩토링 해 보는 예제 입니다.
  

## Task 9: CI/CD 파이프라인 실습 
  - 주어진 파이프라인에 대한 설명과 변환등을 GitHub Copilot을 사용하여 실습하는 예제입니다.



