# PLKIT-FE.web

## 개요

**PLKIT-FE.web** 프로젝트는 농업 데이터를 안전하게 공유하고 거래할 수 있는 스마트 농업 생태계 구축을 목표로 한 플랫폼입니다. 농업 종사자, 연구자, 전문가들이 모여 농업 지식을 교류하고 협업할 수 있는 커뮤니티 공간을 제공합니다. 이 플랫폼을 통해 데이터 기반 스마트 농업을 촉진하며, 사용자는 데이터를 안전하게 관리하고 수익화할 수 있습니다.

---

## 개발 프로그램 설명

### 🌱 지식 공유
커뮤니티 플랫폼을 통해 농업 관련 다양한 지식과 경험을 공유하고, 질문과 답변을 통해 실질적인 문제 해결 방안을 모색할 수 있습니다. 농업 전문가, 연구자, 농업 종사자들이 협력하여 농업 발전에 기여할 수 있는 협력의 장을 제공합니다.

### 🤝 협업 증진
다양한 농업 주제에 대한 협업을 촉진하여 시너지 효과를 창출합니다. 공동 연구 프로젝트, 데이터 공유, 기술 교류 등을 통해 농업 혁신을 지속 가능하게 합니다.

### 🌍 생태계 확장
스마트팜 기술의 도입과 확산을 통해 농업 생태계를 확장하고, 일자리 창출 및 경제적 파급 효과를 기대할 수 있습니다.

---

## 커뮤니티 기능을 통한 데이터 공유

데이터 플랫폼을 통해 사용자들은 농업 데이터를 공유할 수 있으며, 주요 기능은 다음과 같습니다:

- **데이터 등록**: 농업 종사자는 자신의 데이터를 플랫폼에 등록하고 가격을 설정하여 판매할 수 있습니다.
- **데이터 검색**: 구매자는 필요한 데이터를 검색하고 구매할 수 있으며, 이를 통해 데이터 기반의 농업 연구 활성화와 농가 소득 증대에 기여할 수 있습니다.

---

## 제품 차별성

### 농업 데이터 교류 플랫폼

단순한 데이터 모니터링을 넘어, 안전하고 신뢰할 수 있는 데이터 거래를 지원하는 환경을 제공합니다. 주요 차별화 요소는 다음과 같습니다:

- **데이터 수집**: 다양한 센서를 통해 실시간으로 데이터를 수집하고 저장.
- **데이터 익명화**: 개인정보 보호를 위한 데이터 익명화 처리로 데이터의 안전성을 확보.
- **수익 창출**: 데이터 제공자에 대한 수익 분배 모델을 통해 데이터를 제공한 사용자에게 수익 창출의 기회를 제공합니다.

연구 기관과 농업 관련 기업은 필요한 데이터를 구매하여 연구 개발(R&D) 목적으로 활용할 수 있습니다.

---

## 기술 스택 및 개발 방법

이 프로젝트는 **React**를 기반으로 한 **모듈형 컴포넌트 아키텍처**를 사용하여 설계되었습니다. 각 기능이 독립적인 컴포넌트로 구현되어 유지보수성과 확장성을 높였으며, 데이터 통신 및 상태 관리를 최적화했습니다.

- **프론트엔드 프레임워크**: React를 사용하여 컴포넌트 기반으로 설계하였으며, 사용자 경험을 개선하는 동적 웹페이지를 제공합니다.
- **스타일링**: CSS-in-JS 방식의 Styled-Components를 사용하여 유지보수가 용이한 스타일링을 제공합니다.
- **백엔드 연동**: API와 JWT 인증 방식을 기반으로 한 안전한 데이터 통신을 구현하였습니다.

이러한 기술 스택은 플랫폼의 성능과 보안성을 높이며, 다양한 스마트팜 장치와의 통합을 가능하게 합니다.

---

## 프로젝트 디렉토리 구조

```bash
PLKIT-FE.web
├── .env                  # 환경 변수 설정 파일
├── .gitignore            # Git에서 제외할 파일 목록
├── directory_structure.txt # 디렉토리 구조 파일
├── package-lock.json     # npm 패키지 종속성 관리 파일
├── package.json          # 프로젝트 설정 파일
├── README.md             # 프로젝트 설명 파일
├── public
│   ├── index.html        # HTML 템플릿 파일
│   └── imgs              # 이미지 파일 폴더
│       ├── default_1.jpg
│       ├── default_2.jpg
│       └── default_3.jpg
├── src
│   ├── axiosConfig.js    # Axios 설정 파일
│   ├── index.css         # 전역 스타일 파일
│   ├── index.js          # React 앱 진입 파일
│   ├── Main.js           # 메인 컴포넌트
│   ├── setupProxy.js     # 프록시 설정 파일
│   ├── api               # API 폴더
│   │   ├── index.js      # API 요청 관리 파일
│   │   └── mock.json     # 모의 데이터 파일
│   ├── assets            # 프로젝트에 필요한 이미지 및 아이콘
│   │   ├── catalog.svg
│   │   ├── google.svg
│   │   └── (기타 아이콘 파일들)
│   ├── components        # UI 컴포넌트 폴더
│   │   ├── App.js        # 주요 앱 컴포넌트
│   │   ├── Avatar.js     # 사용자 아바타 컴포넌트
│   │   ├── Button.js     # 버튼 컴포넌트
│   │   ├── Card.js       # 카드 컴포넌트
│   │   ├── Footer.js     # 푸터 컴포넌트
│   │   ├── Nav.js        # 네비게이션 컴포넌트
│   │   ├── SearchBar.js  # 검색 바 컴포넌트
│   │   └── (기타 컴포넌트 파일들)
│   ├── contexts          # 컨텍스트 관리 폴더
│   │   ├── AuthProvider.js       # 인증 컨텍스트
│   │   └── ToasterProvider.js    # 토스트 메시지 컨텍스트
│   ├── hooks             # 커스텀 훅 폴더
│   │   └── useIsMounted.js       # 컴포넌트 마운트 확인 훅
│   ├── lib               # 라이브러리 및 유틸리티 폴더
│   │   └── axios.js      # Axios 커스텀 인스턴스
│   ├── pages             # 주요 페이지 폴더
│   │   ├── CommunityListPage.js  # 커뮤니티 리스트 페이지
│   │   ├── CommunityPage.js      # 커뮤니티 상세 페이지
│   │   ├── MarketListPage.js     # 마켓 리스트 페이지
│   │   ├── MarketPage.js         # 마켓 상세 페이지
│   │   ├── LoginPage.js          # 로그인 페이지
│   │   ├── RegisterPage.js       # 회원가입 페이지
│   │   ├── HomePage.js           # 메인 홈 페이지
│   │   ├── NotFoundPage.js       # 404 에러 페이지
│   │   └── (기타 페이지 파일들)
│   └── utils             # 유틸리티 함수 폴더
│       └── getMarketColor.js     # 마켓 컬러 함수
└── node_modules          # 프로젝트 의존성 모듈
```

이 디렉토리 구조는 각 기능과 페이지를 독립적으로 관리하여 코드의 모듈화와 재사용성을 높였으며, 명확한 폴더 구조로 유지보수성을 강화했습니다.


---

## 주요 기능 및 UI 설명

### 사용자 인증 및 접근 제어
- 사용자가 본인 인증을 완료하면, 커뮤니티와 마켓에 접근할 수 있습니다. 인증 완료 후 활성화된 서비스에 접근하여 데이터 공유 및 거래를 진행할 수 있습니다.

![사용자 인증](https://github.com/user-attachments/assets/799c7efb-5ff7-44a7-bea8-1ce3ed3544a4)

### 커뮤니티 (Community)
- **지식 공유**: 커뮤니티에서 사용자들은 스마트팜에 대한 정보와 지식을 자유롭게 공유할 수 있습니다. 질문을 등록하고 답변을 받을 수 있어, 농업 관련 문제를 해결하는 데 도움을 줍니다.

![커뮤니티 페이지](https://github.com/user-attachments/assets/93c0d6bc-2111-4168-aede-220798f07a6a)

- **게시글 관리**: 게시글을 등록, 수정, 삭제할 수 있으며, 다른 사용자의 질문에 대한 답변을 통해 지식을 교류할 수 있습니다.

![커뮤니티 아이템](https://github.com/user-attachments/assets/44781980-2be3-4069-9ca9-0e90ed5e2bac)

- **게시글 상세보기**: 각 게시글의 상세 페이지에서 내용을 확인하고, 추가 질문 및 답변을 통해 소통할 수 있습니다.

![커뮤니티 상세보기](https://

github.com/user-attachments/assets/70612bb2-6be3-4b34-ba0a-e9fb18354cef)

### 마켓 (Market)
- **데이터 거래**: 사용자들이 스마트팜에서 수집한 데이터를 거래할 수 있습니다. 각 데이터에 대한 정보를 입력하고, 가격과 조건을 설정하여 판매할 수 있습니다.

![마켓 페이지](https://github.com/user-attachments/assets/5506ab5f-136b-4ca8-8bd2-3f82ddfe4e8b)

- **거래 데이터 관리**: 판매 중인 데이터의 정보를 수정하거나 삭제할 수 있으며, 데이터에 대한 상세 설명을 추가하여 구매자에게 필요한 정보를 제공합니다.

![마켓 아이템](https://github.com/user-attachments/assets/52a39f47-c2a3-4edc-b215-2bc6908d7b08)

