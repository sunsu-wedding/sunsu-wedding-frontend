# sunsu-wedding-frontend

![순수웨딩 소개](https://github.com/sunsu-wedding/sunsu-wedding-frontend/assets/53530683/da667dbd-809d-4149-a9eb-99593be6e827)

> 목차
>
> - [📌 프로젝트 소개](#프로젝트-소개)
> - [👩‍👩‍👧‍👧 팀원 소개](#팀원-소개)
> - [✏️ 주요 기능](#주요-기능)
> - [⭐️ FE 개발 주안점](#FE-개발-주안점)
> - [🔗 링크 모음(배포 주소 포함)](#링크-모음)
> - [📜 ERD](#erd)
> - [📁 파일 구조](#파일-구조)
> - [🚩 시작 가이드](#시작-가이드)
> - [🖥️ 기술 스택](#기술-스택)
> - [📄 API 모아보기](#api-모아보기)

<br>

## 프로젝트 소개

### 개발 동기 및 목적

예비 부부의 경우 결혼과 관련된 정보를 찾기 위해서는 웨딩 박람회, 온라인 검색, SNS 등 여러 방법을 사용하지만, 어디를 알아봐도 복잡하기만 하고 가격도 천차만별이라 선택하기 어렵습니다. 또한, 결혼 시장의 경우 일회성 고객이 대부분이다 보니 소비자보다 판매자 위주의 시장이 형성되어 왔습니다. 이에 따라 결혼 비용을 공개하지 않아 지인 소개 등으로 가면 훨씬 싸게 해주는 등 소비자 입장에선 모르고 당하기 십상입니다.

웨딩 플래너의 경우 무급으로 시작해서 실력이 아닌 연차가 쌓일 때까지는 최저시급에도 미치지 못하는 기본급을 받으며 열정 페이를 강요받아 어려움을 겪고 있었습니다.

✨ 저희 `순수웨딩` 팀은 앞선 웨딩플래너의 결혼 준비 비용 불투명성 문제와 웨딩 플래너의 급여 공정성 문제를 해결하기 위해 투명한 가격으로 이 둘을 매칭 해주는 서비스를 기획하게 되었습니다. ✨

<br>

### 서비스 소개

> 투명한 가격으로 웨딩 플래너와 예비 부부를 매칭하다, '순수웨딩'

1. ✏️ 투명한 웨딩 플래너의 **포트폴리오**

   - 웨딩 플래너가 직접 등록한 자기 소개, 예상 가격, 사진, 사용자 리뷰등 볼 수 있어요
   - `순수 웨딩 멤버십`에 가입하면 플래너의 실제 이전 계약 기록(업체, 가격, 날짜 등)을 볼 수 있어요
   - 마음에 드는 플래너를 찜할 수 있어요!

2. 🗨️ 내 PICK! 플래너에게 **채팅 상담받기**

   - 원하는 플래너들과 채팅으로 상담받으며 결혼 준비를 할 수 있어요

3. 📜 **견적서**로 결혼 진행 과정을 서로 공유해요

   - 채팅방에서 견적서를 만들어서 업체 이름, 가격 등을 확인하고 진행 상황을 한눈에 확인할 수 있어요
   - 전체 견적서를 확정하면 해당 플래너에 대한 리뷰를 작성할 수 있어요

4. 💯 **리뷰**를 통해 생생한 결혼 진행 후기 확인하기
   - 다른 사람이 실제로 플래너와 진행한 후기를 들려줘요 이를 기반으로 더 좋은 플래너를 선택할 수 있어요
   - 해당 내용은 포트폴리오 상세 페이지에서 확인할 수 있어요

<br>

### 개발 기간

2023.09.04 - 2023.11.11 (카카오 테크 캠퍼스 1기 - 3단계 진행 기간)

<br>

## 팀원 소개

|          [김찬호](https://github.com/kimchanho97)          |           [이현빈](https://github.com/blackhblee)            |          [남원정](https://github.com/1jeongg)          |          [문석준](https://github.com/seokwns)          |          [천영채](https://github.com/chaee813)          |          [김정도](https://github.com/Rizingblare)          |
| :--------------------------------------------------------: |:---------------------------------------------------------:| :----------------------------------------------------: | :----------------------------------------------------: | :-----------------------------------------------------: | :--------------------------------------------------------: |
| <img src="https://github.com/kimchanho97.png" width="100"> | <img src="https://github.com/blackhblee.png" width="100"> | <img src="https://github.com/1jeongg.png" width="100"> | <img src="https://github.com/seokwns.png" width="100"> | <img src="https://github.com/chaee813.png" width="100"> | <img src="https://github.com/Rizingblare.png" width="100"> |
|                             FE                             |                            FE                             |                           BE                           |                           BE                           |                           BE                            |                             BE                             |

<br>

## 주요 기능

> - ✏️ 포트폴리오
> - 🗨️ 채팅 상담
> - 📜 견적서
> - 💯 리뷰
> - 💳 결제

| 포트폴리오 탐색                                                                                                                   | 검색 및 필터링                                                                                                                    |
| --------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------- |
| <img width="380" src="https://github.com/Step3-kakao-tech-campus/Team5_FE/assets/104095041/18e4e9cc-87ed-4053-bec3-fd25e48fda29"> | <img width="380" src="https://github.com/Step3-kakao-tech-campus/Team5_FE/assets/104095041/a52c056e-9912-4062-b926-b1c64eb78eb9"> |
| • 플래너가 등록한 정보, 이미지, 리뷰 등 조회 <br> • 멤버십 사용자 - 이전 계약 정보(가격, 업체 등) 조회 <br>                       | • 지역과 가격 등 필터링 조건 설정 <br> • 플래너 이름 검색                                                                         |

| 채팅 전송                                                                                                              | 채팅 응답                                                                                                                         |
| ---------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------- |
| <img width="380" src="https://github.com/kimchanho97/algorithm/assets/104095041/d3b0faf7-d20c-4e83-9d66-00d2c38253c6"> | <img width="380" src="https://github.com/Step3-kakao-tech-campus/Team5_FE/assets/104095041/0863820b-a151-4551-8c01-c8478e3a49ad"> |
| • 이미지 전송                                                                                                          | • 읽음 유무 표시 <br> • 안 읽은 메시지 개수 표시                                                                                  |

| 포트폴리오 작성 / 수정                                                                                                            | 견적서 작성 / 수정                                                                                                                |
| --------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------- |
| <img width="380" src="https://github.com/Step3-kakao-tech-campus/Team5_FE/assets/104095041/2474a94c-6a19-4e02-b047-500b80b307a6"> | <img width="380" src="https://github.com/Step3-kakao-tech-campus/Team5_FE/assets/104095041/7c2c1e74-4bb1-4682-b26f-51fb07015f1a"> |
| • 플래너의 소개, 가격 등의 정보를 등록 <br> • 수정 및 삭제                                                                        | • 견적서 항목에 대한 정보 등록 <br> • 수정 및 삭제                                                                                |

| 리뷰 작성 / 수정                                                                                                                  | 리뷰 조회                                                                                                                         |
| --------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------- |
| <img width="380" src="https://github.com/Step3-kakao-tech-campus/Team5_FE/assets/104095041/aed20cd4-a50d-4084-ba63-99c00e160de7"> | <img width="380" src="https://github.com/Step3-kakao-tech-campus/Team5_FE/assets/104095041/4997bb5f-aa6e-47d5-a60c-aea1d166f75c"> |
| • 플래너의 별점 및 후기 등록 <br> • 수정 및 삭제                                                                                  | • 해당 플래너의 리뷰 조회                                                                                                         |

| 결제                                                                                                                              | 찜하기                                                                                                                            |
| --------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------- |
| <img width="380" src="https://github.com/Step3-kakao-tech-campus/Team5_FE/assets/104095041/1a03508c-5e5a-43c1-a367-3a8a82f92dcb"> | <img width="380" src="https://github.com/Step3-kakao-tech-campus/Team5_FE/assets/104095041/452e1f91-7115-46f2-83de-7e0e007fce99"> |
| • 토스 페이먼츠 연동 <br> • 결제 승인 & 유저 등급 업그레이드                                                                      | • 찜하기 등록 및 삭제 <br> • 찜하기 모아보기                                                                                      |

<br>

## FE 개발 주안점

### 📌 커서 기반 페이지네이션(Cursor-Based Pagination) 무한 스크롤 적용

순수웨딩 서비스의 웨딩플래너 포트폴리오 탐색 페이지에서는 커서 기반 페이지네이션을 도입하여 페이지 로딩 시, 사용자에게 **중복된 항목 없이 새로운 내용을 제공** 하고 있습니다. 이 방식을 통해 사용자는 웨딩 플래너 포트폴리오를 둘러보며 일관된 경험을 누릴 수 있습니다.

커서 기반 페이지네이션은 전통적인 오프셋 기반 페이지네이션에 비해 여러 가지 장점을 가지고 있습니다. 오프셋 기반 페이지네이션은 페이지 수가 증가함에 따라 성능이 저하되는 반면, 커서 기반 페이지네이션은 **일정한 성능을 유지**합니다. 또한, 사용자가 웨딩 플래너 포트폴리오를 스크롤하는 동안 **데이터의 일관성을 유지**하는 데에도 큰 역할을 합니다. 이는 사용자가 탐색 과정에서 혼란스러움 없이 원활하게 정보를 얻을 수 있게 해주는 중요한 요소입니다. 결과적으로, 커서 기반 페이지네이션 도입은 사용자 경험의 향상과 서비스의 성능 개선에 크게 기여하였습니다.

<br>

### 📌 Firebase Realtime Database를 활용한 채팅

Firebase Realtime Database를 사용하면 기존의 웹 소켓 통신 방식과 HTTP 통신 방식에 비해 여러 가지 이점을 얻을 수 있습니다.

1. **비정상적 연결 끊김에 대한 대응**: 웹 소켓 통신 방식에서는 사용자의 비정상적인 연결 끊김(새로고침, 페이지 닫기 등)에 대응하기 어렵습니다. 이런 상황에서 데이터 전송 중이었다면 그 데이터는 손실되고, 이에 적절하게 대응할려면 코드나 설계가 복잡하고 어렵습니다. 반면, Firebase Realtime Database는 연결이 끊어지더라도 데이터를 로컬에 저장하고, 연결이 복구되면 서버와 자동으로 동기화합니다.

2. **자동 확장성**: 웹 소켓 통신은 사용자가 많아지면 서버 부하가 증가하고, 이를 관리하기 위해 추가적인 서버 리소스가 필요합니다. HTTP 통신 방식에서도 트래픽이 증가하면 서버 부하가 늘어나고, 이를 관리하기 위해 추가적인 서버 리소스가 필요합니다. 반면, Firebase는 자동으로 확장되므로, 트래픽이 증가하더라도 서버를 유지관리할 필요가 없습니다.

3. **실시간 업데이트**: HTTP 통신 방식에서는 새로운 메시지를 확인하기 위해 주기적으로 서버에 요청을 보내야 합니다. 이는 서버 부하를 증가시키고, 실시간 채팅에 필요한 즉각성을 해치게 됩니다. 반면, Firebase는 데이터 변경 시 실시간으로 클라이언트에 업데이트를 제공합니다.

따라서, 이러한 이점들과 개발 리소스를 고려하여 Firebase Realtime Database를 사용하여 채팅 서비스를 구현함으로써 개발 및 유지관리의 효율성을 높일 수 있었습니다. 또한, 실시간 메시지 송수신뿐만 아니라 **상대방의 메시지 읽음 처리, 안 읽은 메시지 개수, 채팅방의 최신 순서 정렬, 그리고 채팅방 이미지 전송** 과 같은 기존의 메신저 앱과 동일한 기능을 제공함으로써 사용자에게는 더 나은 사용자 경험을 제공합니다.

<br>

### 📌 Toss Payments를 연동한 결제 서비스

순수웨딩은 사용자의 편의성을 최우선으로 고려하여 Toss Payments를 연동한 결제 서비스를 구현하였습니다. 이를 통해 **다양한 결제 방식을 지원하며, 사용자의 결제 경험을 한층 개선**하였습니다.

구체적으로, 결제 요청이 발생하면 우선 결제 정보를 서버에 저장합니다. 이후 결제 요청이 이루어지고 인증 과정을 거치게 됩니다. 이 과정이 완료되면 서버에서 결제 정보를 검증하고, **검증 결과가 일치할 경우 결제 승인 및 사용자 등급 업그레이드를 Atomic 하게** 처리합니다. 이러한 절차를 통해 결제의 무결성을 보장하고, 동시에 사용자의 결제 경험을 원활하게 만들어줍니다. 결제 과정 중에 발생할 수 있는 오류를 최소화하고, 사용자의 결제 과정을 안전하고 편리하게 진행할 수 있도록 도와줍니다.

<br>

### 📌 PWA를 활용한 모바일 최적화

순수웨딩은 사용자의 편의성을 극대화하기 위해 PWA(Progressive Web App)를 도입하여 모바일 지원을 강화하였습니다. PWA는 웹과 모바일 앱의 장점을 결합한 기술로, **웹 애플리케이션을 모바일 앱과 유사한 경험으로 제공**하는 것을 목표로 합니다.

PWA는 웹 애플리케이션을 작동시키지만, 사용자에게는 네이티브 모바일 앱과 유사한 경험을 제공합니다. 이는 웹 표준 기술들을 활용하여 구현되며, 특정 플랫폼이나 디바이스에 구애받지 않고 동작할 수 있습니다. 순수웨딩은 웹 사이트를 모바일 앱과 유사하게 만들어, 더욱 직관적이고 사용자 친화적인 UI를 제공합니다. PWA를 활용함으로써 사용자들은 언제 어디서나 원활하게 서비스를 이용할 수 있습니다.

<br>

### 📌 Global BottomSheet & Redux를 활용한 효율적 상태관리

순수웨딩은 깔끔하고 일관된 UI를 제공하기 위해, 에러 메시지나 알림 등의 표시에 Global BottomSheet를 활용하고 있습니다. 이 BottomSheet는 Redux를 통해 상태가 관리되며, **각 하위 컴포넌트에서도 이를 손쉽게 참조하거나 변경할 수 있습니다. 이로써 각 컴포넌트에서 독립적으로 상태를 관리하는 번거로움을 해결**하였습니다.

상태 변경을 더욱 간편하게 만들기 위해, BottomSheet의 **열고 닫는 동작을 관리하는 'useOpenBottomSheet' 커스텀 훅(Custom Hook)** 을 개발하였습니다. 이 훅은 컴포넌트 간의 재사용성을 향상시키고, 상태 관리를 단순화하며, 개발자가 BottomSheet를 쉽게 조작할 수 있게 도와줍니다.

이런 방식을 통해 사용자는 일관된 UI를 경험할 수 있고, 개발 팀은 상태 관리의 복잡성을 줄이며 개발 효율성을 높일 수 있었습니다.

<br>

| 회원탈퇴 바텀시트                                                                                                                 | 로그인 바텀시트                                                                                                                   | 서버에러 바텀시트                                                                                                                 |
| --------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------------------------- |
| <img width="200" src="https://github.com/sunsu-wedding/sunsu-wedding-frontend/assets/53530683/4f3b988d-0414-4381-9e20-0d9cb62188cd"> | <img width="200" src="https://github.com/sunsu-wedding/sunsu-wedding-frontend/assets/53530683/d7c95882-ec4e-4f85-8982-17325edbb72d"> | <img width="200" src="https://github.com/sunsu-wedding/sunsu-wedding-frontend/assets/53530683/f1d64aef-0b6a-475e-813b-d3b833b460f0"> |

<br>

### 📌 체계적이고 효율적인 예외처리

순수웨딩은 예외처리에 있어서 체계적이고 효율적인 접근 방식을 채택하여, 사용자에게 더욱 안정적인 서비스를 제공하기 위해 노력하였습니다.

우선, HTTP 상태 코드로만은 처리하기 힘든 다양한 예외 상황을 대비하기 위해, 팀은 **고유한 상태 코드를 개발하고 API 명세서를 체계적으로 정리**하였습니다. 이를 통해 백엔드와의 의사소통이 원활하게 이루어지며, 복잡한 에러 케이스를 정교하게 처리할 수 있게 되었습니다.

또한, 공통적으로 발생할 수 있는 에러 처리를 위해 'useDefaultErrorHandler'라는 커스텀 훅을 개발하였습니다. 이 훅을 통해, axios 최상위에서 에러를 일괄 처리하는 것이 아니라, **각 컴포넌트에서 발생하는 에러를 우선적으로 처리하고, 그 외의 일반적인 예외 상황은 'defaultErrorHandler'가 처리**하도록 하였습니다. 이 방식은 코드의 재사용성을 높이고, 다양한 에러 상황에 대응할 수 있게 만들었습니다.

<br>

### 📌 서버 부하 감소를 위한 이미지 압축: compressorjs 라이브러리 활용

순수웨딩 서비스에서는 이미지 데이터의 전송에 있어서 multipart/form-data를 이용하여 파일을 전송하고 AWS S3에 이미지를 저장하는 방식을 사용하지 못하게 되었습니다. 대신, Base64로 인코딩된 문자열을 활용하여 이미지 파일의 요청과 응답을 처리하였는데, 이 방식은 서버에 부하를 주는 문제를 야기할 수 있습니다.

이 문제를 해결하기 위해 저희는 'compressorjs' 라이브러리를 활용하여 이미지 압축을 구현하였습니다. 이 라이브러리를 사용하면 이미지 파일을 효율적으로 압축하고, 압축된 데이터를 Base64 문자열로 전환하여 전송할 수 있습니다.

압축 기능을 적용한 결과, **24.4MB 크기의 이미지 파일이 26.2kB**로 줄어들었습니다. 이는 원본 파일 대비 약 931배의 압축률을 보여줍니다(파일마다 압축비는 다를 수 있음). 이렇게 구현된 이미지 압축 기능으로 인해, 요청하는 데이터의 양이 증가하더라도 우리 서비스는 안정적인 응답 시간을 유지할 수 있습니다. 이를 통해, 서버 부하를 효과적으로 관리하며, 성능 향상을 이루어냈습니다.

<br>

### 📌 사용자 경험 향상을 위한 커스텀 훅 활용: usePreventRefresh & usePreventGoback

순수웨딩 서비스에서는 포트폴리오 작성/수정, 리뷰 작성/수정, 견적서 작성/수정 등 다양한 페이지에서 사용자들이 직접 글을 작성하고 관리해야 하는 상황을 마주하게 됩니다. 그러나 사용자가 글을 작성하는 도중에 **무심코 새로고침이나 뒤로가기를 하게 되면, 작성하던 내용이 모두 사라지는 문제가 발생**합니다.

이런 문제를 해결하기 위해, 자동 저장 기능을 고려해 보았지만, 현재 서비스에 등록된 글과 작성 중인 글을 동기화하는 것은 쉽지 않았습니다. 왜냐하면 글은 사용자의 확정에 따라 등록 또는 수정이 완료되어야 하기 때문입니다. 또한, 작성 중인 글을 별도로 데이터베이스에 저장하는 방식은 불필요한 저장 공간을 차지하게 되는 문제점이 있었습니다.

이에 저희 팀은 사용자 경험을 향상시키기 위해 'usePreventRefresh'와 'usePreventGoback'이라는 커스텀 훅을 제작하였습니다. 이 커스텀 훅들은 **글 작성 중에 뒤로가기나 새로고침을 하게 될 경우, 경고문을 띄워 사용자에게 작성 중인 내용이 사라질 수 있음을 알려주고 한 번 더 확인을 받는 방식으로 작동**합니다. 이런 방식을 통해, 사용자는 실수로 작성 중인 내용을 잃어버리는 상황을 피할 수 있게 되었고, 커스텀 훅의 재사용성을 통해 코드의 효율성이 향상되었습니다. 이렇게 현 상황에서 최선의 방법을 찾아 문제를 해결하고, 사용자 경험을 향상시킬 수 있었습니다.

<br>
<br>

## 링크 모음

| 기획                                                                                                                                                                                              | 디자인                                                                                                                                     | 개발                                                                                                                    | 배포                                                                                        |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------ | ----------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------- |
| [노션](https://unmarred-belief-362.notion.site/f11783c42731479ca1f6c9a97a738324?pvs=4)                                                                                                            | [와이어프레임](https://www.figma.com/file/Wcz9d59GIQqwTEAfIEmRly/SUNSU-WEDDING?type=design&node-id=0%3A1&mode=design&t=5PnD2GPs3WktbNNy-1) | [백엔드 깃허브](https://github.com/Step3-kakao-tech-campus/Team5_BE)                                                    | [프론트 배포 주소(크램폴린 만료)](https://k5c1813d97f50a.user-app.krampoline.com/)          |
| [기획안 PPT](https://www.figma.com/file/A81sCNiwoLUfSe5aqXEHXr/%EC%B9%B4%ED%85%8C%EC%BA%A0-5%EC%A1%B0---%EA%B8%B0%ED%9A%8D%EC%95%88?type=design&node-id=972-145&mode=design&t=QdcoBgtPZi631myk-0) |                                                                                                                                            | [ERD](https://www.erdcloud.com/d/fww6HRj7oXL9cdp5t)                                                                     | [백엔드 / 풀스택 배포 주소(크램폴린 만료)](https://k0b2de7d86228a.user-app.krampoline.com/) |
| [Survey](https://unmarred-belief-362.notion.site/Survey-a4c9ba9b8114456f88faa61b33f232c9)                                                                                                         |                                                                                                                                            | [API 문서](https://unmarred-belief-362.notion.site/6fd74038970941a2ad02df0045705095?v=545b8da990c74661b2b6b560009766ff) | [시연 영상](https://www.youtube.com/watch?v=WfDcwd8AQNQ)                                    |
|                                                                                                                                                                                                   |                                                                                                                                            | [테스트 시나리오 명세서](https://unmarred-belief-362.notion.site/FE-93d000ab86f44dcf8ea1c99d8d0b1fa4?pvs=4)             |                                                                                             |
|                                                                                                                                                                                                   |                                                                                                                                            | [테스트 결과 보고서](https://unmarred-belief-362.notion.site/FE-abc1a99b7e14459ea5e8ee25957a3053?pvs=4)                 |                                                                                             |

<br>

## ERD

![ERD](https://github.com/sunsu-wedding/sunsu-wedding-frontend/assets/53530683/32eb5c96-b1a9-40fb-8679-0c8e503fa8c1)

## 파일 구조

```
├───📂public
│   ├───📂icons
│   └───📂images
└───📂src
    ├───📂apis
    ├───📂assets
    ├───📂components
    │   ├───📁chat
    │   ├───📁common
    │   │   ├───📁accounts
    │   │   ├───📁atoms
    │   │   ├───📁bottomsheet
    │   │   └───📁modal
    │   ├───📁createportfolio
    │   ├───📁favorite
    │   ├───📁main
    │   ├───📁portfoliodetail
    │   ├───📁portfolios
    │   ├───📁profile
    │   ├───📁quotation
    │   └───📁review
    ├───📂firebase
    ├───📂hooks
    ├───📂layouts
    ├───📂mocks
    ├───📂pages
    ├───📂store
    │   ├───📁atoms
    │   └───📁slices
    └───📂utils
```

<br>

## 시작 가이드

> Requirements: Node.js 18.x, npm 10.x
>
> 순수웨딩 환경 변수 설정이 완료되어야 프로젝트가 실행됩니다.

1. 프로젝트 클론

```bash
git clone https://github.com/sunsu-wedding/sunsu-wedding-frontend.git
cd sunsu-wedding-frontend
```

2. 실행

```bash
npm install
npm start
```

<br>

## 기술 스택

![기술 스택)](https://github.com/sunsu-wedding/sunsu-wedding-frontend/assets/53530683/f47b0d3d-5cdd-4e27-9f49-522772d7ff69)

<br>

## 프레임워크/라이브러리

![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=React&logoColor=white)
![React Router](https://img.shields.io/badge/React_Router-CA4245?style=flat-square&logo=React-Router&logoColor=white)
![React Query](https://img.shields.io/badge/React_Query-FF4154?style=flat-square&logo=React-Query&logoColor=white)
![Redux](https://img.shields.io/badge/Redux-764ABC?style=flat-square&logo=Redux&logoColor=white)
![Redux Persist](https://img.shields.io/badge/Redux_Persist-764ABC?style=flat-square&logo=Redux&logoColor=white)
<br>
![Jotai](https://img.shields.io/badge/Jotai-000000?style=flat-square&logo=jotai&logoColor=ffffff&labelColor=000000)
![Axios](https://img.shields.io/badge/Axios-5A29E4?style=flat-square&logo=Axios&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=Firebase&logoColor=white)
![Lodash](https://img.shields.io/badge/Lodash-3492FF?style=flat-square&logo=Lodash&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

<br>

## API 모아보기

|이름|url|사용자|메서드|
|:--|:--|:----|:-----|
|//회원//||||
|👤 회원가입|	/api/user/signup|	`공통`	|`POST`|
|👤 로그인|	/api/user/login	|`공통`	|`POST`|
|👤 유저 정보 조회|	/api/user/info	| `공통`	|`GET`|
|👤 토큰 갱신|	/api/user/token	|`공통`	| `POST` |
|👤 회원탈퇴|	/api/user	|`공통`|	`DELETE`|
|// 이메일 //			||||
|✉️ 이메일 인증 코드 전송|	/api/mail	|`공통`	|`POST`|
|✉️ 이메일 인증 코드 검증|	/api/mail/verify|	`공통`|	`POST`|
|// 결제 //			||||
|💳 결제 데이터 저장|	/api/payment/save|	`공통`|	`POST`|
|💳 결제 승인 및 업그레이드|	/api/payment/approve|	`공통`|	`POST` |
|// 포트폴리오 //			||||
|✏️ 게시글 리스트 조회|	/api/portfolio?cursor={nextCursor}	|`공통`|	`GET`|
|✏️본인 게시글 조회(플래너)|	/api/portfolio/self|	`웨딩 플래너`|	`GET`|
|✏️상세 게시글 조회|	/api/portfolio/{portfolio_id} |	`공통`|	`GET`|
|✏️게시글 등록|	/api/portfolio	|`웨딩 플래너`	|`POST`|
|✏️게시글 수정	|/api/portfolio	|`웨딩 플래너`|	`PUT`|
|✏️게시글 삭제|	/api/portfolio	|`웨딩 플래너`|	`DELETE`|
|// 채팅 //			||||
|🗨️ 채팅방 생성하기|	/api/chat	|`예비 부부`	|`POST`|
|// 매칭 //			||||
|📌 매칭 확정(견적서 전체 확정)|	/api/match/confirm?chatId={chatId}	|`예비 부부`|	`POST`|
|📌 리뷰 작성 가능한 매칭 조회|	/api/match/review	|`예비 부부`|	`GET`|
|// 견적서 //			||||
|📜 견적서 전체 리스트 조회|	/api/quotation/all?page={page}	|`공통`	|`GET`|
|📜 견적서 매칭별 리스트 조회	|/api/quotation?chatId={chatId}|	`공통`	|`GET`|
|📜 견적서 등록|	/api/quotation?chatId={chatId}|	`웨딩 플래너`	`POST`|
|📜 견적서 수정|	/api/quotation/{quotationId}?chatId={chatId}|	`웨딩 플래너`	|`PUT`|
|📜 견적서 1개 확정	|/api/quotation/confirm/{quotationId}?chatId={chatId}	|`웨딩 플래너`|	`POST`|
|📜 견적서 삭제|	/api/quotation/{quotationId}	|`웨딩 플래너`|	`DELETE`|
|// 리뷰 //			||||
|💯 리뷰 전체 리스트 조회	|/api/review/all	|`예비 부부`|`GET`|
|💯 리뷰 플래너별 리스트 조회	|/api/review?plannerId={plannerId}&page={page}	|`공통`|	`GET`|
|💯 리뷰 상세 조회|	/api/review/{reviewId}	|`예비 부부`	|`GET`|
|💯 리뷰 등록|	/api/review?chatId={chatId}	|`예비 부부`|`POST`|
|💯 리뷰 수정|	/api/review/{reviewId}|	`예비 부부`|	`PUT`|
|💯 리뷰 삭제	|/api/review/{reviewId}	|`예비 부부`|	`DELETE`|
|// 찜하기 //			||||
|❤️ 찜 전체 리스트 조회	| /api/favorite?page={page}	|`공통`|	`GET`|
|❤️ 찜 등록하기	|/api/favorite/{portfolioId}	|`공통`|	`POST`|
|❤️ 찜 삭제하기	|/api/favorite/{portfolioId}|	`공통`	|`DELETE`|

