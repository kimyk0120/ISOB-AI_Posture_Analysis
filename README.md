# [ISOB - AI 기반 자세 분석 애플리케이션](https://play.google.com/store/apps/details?id=com.isob)

### ▶️ ISOB?

**ISOB는 접근성이 뛰어난 스마트폰을 활용하여 자세 분석을 보다 쉽고 효과적으로 할 수 있도록 돕는 애플리케이션입니다. 
인공지능을 기반으로 한 자동 인체 인식 기술과 의학적 알고리즘을 통해 사용자의 자세를 정밀하게 분석하며, 시계열 데이터 기록과 그래프 기능을 통해 자세 변화를 추적할 수 있도록 설계되었습니다. 
또한, 분석 결과를 효율적으로 관리할 수 있는 기능을 제공하여 사용자들이 자신의 건강을 보다 체계적으로 관리할 수 있도록 돕습니다.**  

[다운로드링크](https://play.google.com/store/apps/details?id=com.isob)

### ▶️ ISOB의 주요 기능

### 📌  스마트폰 기반의 인공지능 자세 분석

ISOB는 이동과 휴대가 편리한 스마트폰을 활용하여 자세 분석을 수행합니다. 인공지능 기반의 자동 인체 인식 기술을 적용하여 사용자의 신체를 정확하게 감지하고 분석할 수 있습니다. 이를 통해 사용자는 별도의 추가 장비 없이 스마트폰 하나만으로도 정밀한 자세 분석을 경험할 수 있습니다.

### 📌 4가지 주요 자세에 대한 분석 제공

의학적 알고리즘을 바탕으로, ISOB는 사용자의 네 가지 주요 자세에 대한 분석을 제공합니다. 분석 항목은 다음과 같습니다.

- **거북목(Turtle Neck Syndrome)**: 목이 앞으로 돌출되는 자세를 감지하고 경추 상태를 분석합니다.
- **어깨 균형(Shoulder Balance)**: 양쪽 어깨의 균형 상태를 분석하여 좌우 높이 차이를 감지합니다.
- **골반 균형(Pelvic Balance)**: 골반의 기울어짐 여부를 확인하여 신체 중심의 균형 상태를 분석합니다.
- **OX 다리(O/X Leg Analysis)**: 다리 정렬 상태를 분석하여 O자형 혹은 X자형 다리 여부를 판별합니다.

이러한 분석 결과를 통해 사용자는 자신의 신체 균형을 보다 정확하게 이해하고, 필요에 따라 적절한 교정 및 운동 계획을 세울 수 있습니다.

### 📌 시계열 데이터 기록 및 변화 추이 제공

ISOB는 사용자 자세의 변화를 추적할 수 있도록 분석 데이터를 시계열로 기록합니다. 이를 통해 사용자는 특정 기간 동안의 변화 추이를 그래프로 확인할 수 있으며, 자세 개선 여부를 한눈에 파악할 수 있습니다. 이러한 기능은 특히 지속적인 관리가 필요한 사용자들에게 큰 도움이 됩니다.

### 📌 분석 결과의 손쉬운 관리

ISOB는 사용자가 자신의 분석 결과를 손쉽게 관리할 수 있도록 빠른 검색 기능을 제공합니다. 분석 데이터가 쌓여도 손쉽게 과거 기록을 찾아볼 수 있습니다. 이를 통해 사용자들은 자신의 자세 변화를 효과적으로 모니터링하고, 개선 목표를 설정할 수 있습니다.

![Screenshot_20250224_165448_isob.jpg](isob_img_01.png)


---


### 📱 프로젝트 계기

ISOB은 두 명의 개발 스터디 팀원으로 구성된 TEAMK의 사이드 프로젝트로 시작되었습니다. 

프로젝트의 발단은 팀원의 가족 중 한 명이 필라테스 센터를 운영하며, 회원들의 자세 분석과 교정에 도움을 줄 수 있는 애플리케이션이 있으면 좋겠다는 의견을 제시하면서 시작되었습니다. 

기존의 자세 동작 분석 기기는 가격이 높아 접근성이 떨어지는 문제가 있었기 때문에, 우리는 스마트폰을 활용하여 누구나 손쉽게 자세를 분석할 수 있는 기본에 충실한 애플리케이션을 개발하기로 결정하였습니다.  


### 📱개발 스택

ISOB은 다음의 기술을 사용하여 개발되었습니다. 

📱 **프론트엔드**: React Native, Android

💻 **백엔드**: Java, Spring Boot, JPA, Swagger, JWT, Security, QueryDSL, Lombok

🗄️ **데이터베이스**: MariaDB

🎨 **UI**: Figma

🤝 **협업 도구**: Jira 애자일보드

🔄 CI/CD : Github Action

☁️ Cloud : Oracle Cloud  


### 🔹 개발 프레임워크

ISOB 프로젝트에서는 **React Native**와 **Spring Boot**를 선택하여 프론트엔드와 백엔드 개발을 진행하였습니다.

**React Native**는 JavaScript를 사용해 네이티브 앱을 개발할 수 있는 프레임워크로, 기존의 웹 개발 경험을 바탕으로 모바일 앱 개발을 할 수 있다는 장점이 있었습니다. 특히 **React**와 비슷한 디자인 패턴을 따르므로, 개발자가 쉽게 적응할 수 있고, 한 번의 코드 작성으로 **iOS**와 **Android** 두 플랫폼에 동시에 앱을 배포할 수 있습니다. 이러한 특징 덕분에 개발 기간을 단축시키고 유지보수를 용이하게 만들었습니다.

**Spring Boot**는 **Java** 기반의 백엔드 개발 프레임워크로, 숙련된 프레임 워크여서 간편하고 빠르게 애플리케이션을 구축할 수 있어 백엔드 개발에 최적화된 선택이었습니다. **JPA**와 **QueryDSL**을 통해 데이터베이스와의 연동을 효율적으로 처리하고, **Spring Security**와 **JWT**로 보안을 강화하여 안정적인 백엔드 환경을 구축할 수 있었습니다. 또한, RESTful API 서버를 쉽게 구성할 수 있어 프론트엔드와의 연동이 원활하게 이루어졌습니다.  


### 🔹 **협업 도구**

ISOB 프로젝트에서는 **Jira의 애자일 보드**를 활용하여 업무를 분배하고 체계적으로 관리하였습니다. 이를 통해 각 팀원의 진행 상황을 한눈에 파악하고, 효율적인 협업이 가능하도록 하였습니다.

![스크린샷 2025-02-24 오후 6.02.39.png](%E1%84%80%E1%85%A2%E1%84%87%E1%85%A1%E1%86%AF%20%E1%84%8B%E1%85%A7%E1%84%8C%E1%85%A5%E1%86%BC%201a3b87d10c7c80788cc7c606326517a8/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA_2025-02-24_%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE_6.02.39.png)  


### 🔹 **UI/UX 설계**

사용자 경험을 고려한 UI 디자인을 위해 **Figma**를 활용하여 화면 구성을 정의하고 시각적인 요소를 설계하였습니다. 이를 통해 프로젝트의 방향성과 디자인 일관성을 유지하며, 개발 단계에서 원활한 협업이 이루어질 수 있도록 하였습니다.

![스크린샷 2025-02-24 오후 6.05.55.png](%E1%84%80%E1%85%A2%E1%84%87%E1%85%A1%E1%86%AF%20%E1%84%8B%E1%85%A7%E1%84%8C%E1%85%A5%E1%86%BC%201a3b87d10c7c80788cc7c606326517a8/e304f291-7789-48e7-b77e-bc76846e8124.png)  


### 🔹 **API 설계 및 문서화**

백엔드와 프론트엔드 간 원활한 연동을 위해 **Swagger**를 사용하여 API 인터페이스를 정의하고 공유하였습니다. 이를 통해 팀원 간 명확한 API 구조를 설정하고, 협업 시 불필요한 의사소통 비용을 줄일 수 있도록 하였습니다.

![스크린샷 2025-02-24 오후 6.10.09.png](%E1%84%80%E1%85%A2%E1%84%87%E1%85%A1%E1%86%AF%20%E1%84%8B%E1%85%A7%E1%84%8C%E1%85%A5%E1%86%BC%201a3b87d10c7c80788cc7c606326517a8/c0dd6cdc-c011-467a-b4cc-a14c051bc91d.png)  


### 🔹 **데이터베이스 설계**

데이터 모델링 및 스키마 정의를 위해 **ERD Cloud**를 활용하여 ERD를 설계하고 관리하였습니다. 이를 통해 데이터 구조를 시각화하고, 일관된 데이터 모델을 유지하면서 효과적인 데이터베이스 설계가 이루어졌습니다.

![스크린샷 2025-02-24 오후 6.12.06.png](%E1%84%80%E1%85%A2%E1%84%87%E1%85%A1%E1%86%AF%20%E1%84%8B%E1%85%A7%E1%84%8C%E1%85%A5%E1%86%BC%201a3b87d10c7c80788cc7c606326517a8/579e5c37-a415-4992-aed2-1c30cd55d20f.png)  


### 🔹 CI/CD

ISOB 프로젝트에서는 **Github Action**을 사용하여 **CI/CD 파이프라인**을 구축하였습니다. 이를 통해 코드 변경이 있을 때마다 자동으로 빌드, 테스트, 배포 과정이 이루어지도록 설정하였습니다.

![스크린샷 2025-02-24 오후 6.34.59.png](%E1%84%80%E1%85%A2%E1%84%87%E1%85%A1%E1%86%AF%20%E1%84%8B%E1%85%A7%E1%84%8C%E1%85%A5%E1%86%BC%201a3b87d10c7c80788cc7c606326517a8/%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA_2025-02-24_%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE_6.34.59.png)  


### 🔹 AI 라이브러리 개발

JNI를 활용해 C++에서 Java의 AssetManager를 호출하여 TFLite 모델 파일을 바이너리로 로드하였으며, C++과 OpenCV를 사용해 데이터 전처리를 수행하고, TFLite의 Movenet 모델을 GPU 모드로 최적화하여 추론을 실행하였습니다.  

---

<!-- ![Teamk](teamk.png) -->


<html><head><meta http-equiv="Content-Type" content="text/html; charset=utf-8"/><title>TEAMK</title><style>
/* cspell:disable-file */
/* webkit printing magic: print all background colors */
html {
	-webkit-print-color-adjust: exact;
}
* {
	box-sizing: border-box;
	-webkit-print-color-adjust: exact;
}

html,
body {
	margin: 0;
	padding: 0;
}
@media only screen {
	body {
		margin: 2em auto;
		max-width: 900px;
		color: rgb(55, 53, 47);
	}
}

body {
	line-height: 1.5;
	white-space: pre-wrap;
}

a,
a.visited {
	color: inherit;
	text-decoration: underline;
}

.pdf-relative-link-path {
	font-size: 80%;
	color: #444;
}

h1,
h2,
h3 {
	letter-spacing: -0.01em;
	line-height: 1.2;
	font-weight: 600;
	margin-bottom: 0;
}

.page-title {
	font-size: 2.5rem;
	font-weight: 700;
	margin-top: 0;
	margin-bottom: 0.75em;
}

h1 {
	font-size: 1.875rem;
	margin-top: 1.875rem;
}

h2 {
	font-size: 1.5rem;
	margin-top: 1.5rem;
}

h3 {
	font-size: 1.25rem;
	margin-top: 1.25rem;
}

.source {
	border: 1px solid #ddd;
	border-radius: 3px;
	padding: 1.5em;
	word-break: break-all;
}

.callout {
	border-radius: 3px;
	padding: 1rem;
}

figure {
	margin: 1.25em 0;
	page-break-inside: avoid;
}

figcaption {
	opacity: 0.5;
	font-size: 85%;
	margin-top: 0.5em;
}

mark {
	background-color: transparent;
}

.indented {
	padding-left: 1.5em;
}

hr {
	background: transparent;
	display: block;
	width: 100%;
	height: 1px;
	visibility: visible;
	border: none;
	border-bottom: 1px solid rgba(55, 53, 47, 0.09);
}

img {
	max-width: 100%;
}

@media only print {
	img {
		max-height: 100vh;
		object-fit: contain;
	}
}

@page {
	margin: 1in;
}

.collection-content {
	font-size: 0.875rem;
}

.column-list {
	display: flex;
	justify-content: space-between;
}

.column {
	padding: 0 1em;
}

.column:first-child {
	padding-left: 0;
}

.column:last-child {
	padding-right: 0;
}

.table_of_contents-item {
	display: block;
	font-size: 0.875rem;
	line-height: 1.3;
	padding: 0.125rem;
}

.table_of_contents-indent-1 {
	margin-left: 1.5rem;
}

.table_of_contents-indent-2 {
	margin-left: 3rem;
}

.table_of_contents-indent-3 {
	margin-left: 4.5rem;
}

.table_of_contents-link {
	text-decoration: none;
	opacity: 0.7;
	border-bottom: 1px solid rgba(55, 53, 47, 0.18);
}

table,
th,
td {
	border: 1px solid rgba(55, 53, 47, 0.09);
	border-collapse: collapse;
}

table {
	border-left: none;
	border-right: none;
}

th,
td {
	font-weight: normal;
	padding: 0.25em 0.5em;
	line-height: 1.5;
	min-height: 1.5em;
	text-align: left;
}

th {
	color: rgba(55, 53, 47, 0.6);
}

ol,
ul {
	margin: 0;
	margin-block-start: 0.6em;
	margin-block-end: 0.6em;
}

li > ol:first-child,
li > ul:first-child {
	margin-block-start: 0.6em;
}

ul > li {
	list-style: disc;
}

ul.to-do-list {
	padding-inline-start: 0;
}

ul.to-do-list > li {
	list-style: none;
}

.to-do-children-checked {
	text-decoration: line-through;
	opacity: 0.375;
}

ul.toggle > li {
	list-style: none;
}

ul {
	padding-inline-start: 1.7em;
}

ul > li {
	padding-left: 0.1em;
}

ol {
	padding-inline-start: 1.6em;
}

ol > li {
	padding-left: 0.2em;
}

.mono ol {
	padding-inline-start: 2em;
}

.mono ol > li {
	text-indent: -0.4em;
}

.toggle {
	padding-inline-start: 0em;
	list-style-type: none;
}

/* Indent toggle children */
.toggle > li > details {
	padding-left: 1.7em;
}

.toggle > li > details > summary {
	margin-left: -1.1em;
}

.selected-value {
	display: inline-block;
	padding: 0 0.5em;
	background: rgba(206, 205, 202, 0.5);
	border-radius: 3px;
	margin-right: 0.5em;
	margin-top: 0.3em;
	margin-bottom: 0.3em;
	white-space: nowrap;
}

.collection-title {
	display: inline-block;
	margin-right: 1em;
}

.page-description {
	margin-bottom: 2em;
}

.simple-table {
	margin-top: 1em;
	font-size: 0.875rem;
	empty-cells: show;
}
.simple-table td {
	height: 29px;
	min-width: 120px;
}

.simple-table th {
	height: 29px;
	min-width: 120px;
}

.simple-table-header-color {
	background: rgb(247, 246, 243);
	color: black;
}
.simple-table-header {
	font-weight: 500;
}

time {
	opacity: 0.5;
}

.icon {
	display: inline-block;
	max-width: 1.2em;
	max-height: 1.2em;
	text-decoration: none;
	vertical-align: text-bottom;
	margin-right: 0.5em;
}

img.icon {
	border-radius: 3px;
}

.user-icon {
	width: 1.5em;
	height: 1.5em;
	border-radius: 100%;
	margin-right: 0.5rem;
}

.user-icon-inner {
	font-size: 0.8em;
}

.text-icon {
	border: 1px solid #000;
	text-align: center;
}

.page-cover-image {
	display: block;
	object-fit: cover;
	width: 100%;
	max-height: 30vh;
}

.page-header-icon {
	font-size: 3rem;
	margin-bottom: 1rem;
}

.page-header-icon-with-cover {
	margin-top: -0.72em;
	margin-left: 0.07em;
}

.page-header-icon img {
	border-radius: 3px;
}

.link-to-page {
	margin: 1em 0;
	padding: 0;
	border: none;
	font-weight: 500;
}

p > .user {
	opacity: 0.5;
}

td > .user,
td > time {
	white-space: nowrap;
}

input[type="checkbox"] {
	transform: scale(1.5);
	margin-right: 0.6em;
	vertical-align: middle;
}

p {
	margin-top: 0.5em;
	margin-bottom: 0.5em;
}

.image {
	border: none;
	margin: 1.5em 0;
	padding: 0;
	border-radius: 0;
	text-align: center;
}

.code,
code {
	background: rgba(135, 131, 120, 0.15);
	border-radius: 3px;
	padding: 0.2em 0.4em;
	border-radius: 3px;
	font-size: 85%;
	tab-size: 2;
}

code {
	color: #eb5757;
}

.code {
	padding: 1.5em 1em;
}

.code-wrap {
	white-space: pre-wrap;
	word-break: break-all;
}

.code > code {
	background: none;
	padding: 0;
	font-size: 100%;
	color: inherit;
}

blockquote {
	font-size: 1.25em;
	margin: 1em 0;
	padding-left: 1em;
	border-left: 3px solid rgb(55, 53, 47);
}

.bookmark {
	text-decoration: none;
	max-height: 8em;
	padding: 0;
	display: flex;
	width: 100%;
	align-items: stretch;
}

.bookmark-title {
	font-size: 0.85em;
	overflow: hidden;
	text-overflow: ellipsis;
	height: 1.75em;
	white-space: nowrap;
}

.bookmark-text {
	display: flex;
	flex-direction: column;
}

.bookmark-info {
	flex: 4 1 180px;
	padding: 12px 14px 14px;
	display: flex;
	flex-direction: column;
	justify-content: space-between;
}

.bookmark-image {
	width: 33%;
	flex: 1 1 180px;
	display: block;
	position: relative;
	object-fit: cover;
	border-radius: 1px;
}

.bookmark-description {
	color: rgba(55, 53, 47, 0.6);
	font-size: 0.75em;
	overflow: hidden;
	max-height: 4.5em;
	word-break: break-word;
}

.bookmark-href {
	font-size: 0.75em;
	margin-top: 0.25em;
}

.sans { font-family: ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI Variable Display", "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol"; }
.code { font-family: "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace; }
.serif { font-family: Lyon-Text, Georgia, ui-serif, serif; }
.mono { font-family: iawriter-mono, Nitti, Menlo, Courier, monospace; }
.pdf .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI Variable Display", "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK JP'; }
.pdf:lang(zh-CN) .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI Variable Display", "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK SC'; }
.pdf:lang(zh-TW) .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI Variable Display", "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK TC'; }
.pdf:lang(ko-KR) .sans { font-family: Inter, ui-sans-serif, -apple-system, BlinkMacSystemFont, "Segoe UI Variable Display", "Segoe UI", Helvetica, "Apple Color Emoji", Arial, sans-serif, "Segoe UI Emoji", "Segoe UI Symbol", 'Twemoji', 'Noto Color Emoji', 'Noto Sans CJK KR'; }
.pdf .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK JP'; }
.pdf:lang(zh-CN) .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK SC'; }
.pdf:lang(zh-TW) .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK TC'; }
.pdf:lang(ko-KR) .code { font-family: Source Code Pro, "SFMono-Regular", Menlo, Consolas, "PT Mono", "Liberation Mono", Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK KR'; }
.pdf .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK JP'; }
.pdf:lang(zh-CN) .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK SC'; }
.pdf:lang(zh-TW) .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK TC'; }
.pdf:lang(ko-KR) .serif { font-family: PT Serif, Lyon-Text, Georgia, ui-serif, serif, 'Twemoji', 'Noto Color Emoji', 'Noto Serif CJK KR'; }
.pdf .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK JP'; }
.pdf:lang(zh-CN) .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK SC'; }
.pdf:lang(zh-TW) .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK TC'; }
.pdf:lang(ko-KR) .mono { font-family: PT Mono, iawriter-mono, Nitti, Menlo, Courier, monospace, 'Twemoji', 'Noto Color Emoji', 'Noto Sans Mono CJK KR'; }
.highlight-default {
	color: rgba(55, 53, 47, 1);
}
.highlight-gray {
	color: rgba(120, 119, 116, 1);
	fill: rgba(120, 119, 116, 1);
}
.highlight-brown {
	color: rgba(159, 107, 83, 1);
	fill: rgba(159, 107, 83, 1);
}
.highlight-orange {
	color: rgba(217, 115, 13, 1);
	fill: rgba(217, 115, 13, 1);
}
.highlight-yellow {
	color: rgba(203, 145, 47, 1);
	fill: rgba(203, 145, 47, 1);
}
.highlight-teal {
	color: rgba(68, 131, 97, 1);
	fill: rgba(68, 131, 97, 1);
}
.highlight-blue {
	color: rgba(51, 126, 169, 1);
	fill: rgba(51, 126, 169, 1);
}
.highlight-purple {
	color: rgba(144, 101, 176, 1);
	fill: rgba(144, 101, 176, 1);
}
.highlight-pink {
	color: rgba(193, 76, 138, 1);
	fill: rgba(193, 76, 138, 1);
}
.highlight-red {
	color: rgba(212, 76, 71, 1);
	fill: rgba(212, 76, 71, 1);
}
.highlight-default_background {
	color: rgba(55, 53, 47, 1);
}
.highlight-gray_background {
	background: rgba(248, 248, 247, 1);
}
.highlight-brown_background {
	background: rgba(244, 238, 238, 1);
}
.highlight-orange_background {
	background: rgba(251, 236, 221, 1);
}
.highlight-yellow_background {
	background: rgba(251, 243, 219, 1);
}
.highlight-teal_background {
	background: rgba(237, 243, 236, 1);
}
.highlight-blue_background {
	background: rgba(231, 243, 248, 1);
}
.highlight-purple_background {
	background: rgba(248, 243, 252, 1);
}
.highlight-pink_background {
	background: rgba(252, 241, 246, 1);
}
.highlight-red_background {
	background: rgba(253, 235, 236, 1);
}
.block-color-default {
	color: inherit;
	fill: inherit;
}
.block-color-gray {
	color: rgba(120, 119, 116, 1);
	fill: rgba(120, 119, 116, 1);
}
.block-color-brown {
	color: rgba(159, 107, 83, 1);
	fill: rgba(159, 107, 83, 1);
}
.block-color-orange {
	color: rgba(217, 115, 13, 1);
	fill: rgba(217, 115, 13, 1);
}
.block-color-yellow {
	color: rgba(203, 145, 47, 1);
	fill: rgba(203, 145, 47, 1);
}
.block-color-teal {
	color: rgba(68, 131, 97, 1);
	fill: rgba(68, 131, 97, 1);
}
.block-color-blue {
	color: rgba(51, 126, 169, 1);
	fill: rgba(51, 126, 169, 1);
}
.block-color-purple {
	color: rgba(144, 101, 176, 1);
	fill: rgba(144, 101, 176, 1);
}
.block-color-pink {
	color: rgba(193, 76, 138, 1);
	fill: rgba(193, 76, 138, 1);
}
.block-color-red {
	color: rgba(212, 76, 71, 1);
	fill: rgba(212, 76, 71, 1);
}
.block-color-default_background {
	color: inherit;
	fill: inherit;
}
.block-color-gray_background {
	background: rgba(248, 248, 247, 1);
}
.block-color-brown_background {
	background: rgba(244, 238, 238, 1);
}
.block-color-orange_background {
	background: rgba(251, 236, 221, 1);
}
.block-color-yellow_background {
	background: rgba(251, 243, 219, 1);
}
.block-color-teal_background {
	background: rgba(237, 243, 236, 1);
}
.block-color-blue_background {
	background: rgba(231, 243, 248, 1);
}
.block-color-purple_background {
	background: rgba(248, 243, 252, 1);
}
.block-color-pink_background {
	background: rgba(252, 241, 246, 1);
}
.block-color-red_background {
	background: rgba(253, 235, 236, 1);
}
.select-value-color-uiBlue { background-color: undefined; }
.select-value-color-pink { background-color: rgba(225, 136, 179, 0.27); }
.select-value-color-purple { background-color: rgba(168, 129, 197, 0.27); }
.select-value-color-green { background-color: rgba(123, 183, 129, 0.27); }
.select-value-color-gray { background-color: rgba(84, 72, 49, 0.15); }
.select-value-color-transparentGray { background-color: undefined; }
.select-value-color-translucentGray { background-color: undefined; }
.select-value-color-orange { background-color: rgba(224, 124, 57, 0.27); }
.select-value-color-brown { background-color: rgba(210, 162, 141, 0.35); }
.select-value-color-red { background-color: rgba(244, 171, 159, 0.4); }
.select-value-color-yellow { background-color: rgba(236, 191, 66, 0.39); }
.select-value-color-blue { background-color: rgba(93, 165, 206, 0.27); }
.select-value-color-pageGlass { background-color: undefined; }
.select-value-color-washGlass { background-color: undefined; }

.checkbox {
	display: inline-flex;
	vertical-align: text-bottom;
	width: 16;
	height: 16;
	background-size: 16px;
	margin-left: 2px;
	margin-right: 5px;
}

.checkbox-on {
	background-image: url("data:image/svg+xml;charset=UTF-8,%3Csvg%20width%3D%2216%22%20height%3D%2216%22%20viewBox%3D%220%200%2016%2016%22%20fill%3D%22none%22%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%3E%0A%3Crect%20width%3D%2216%22%20height%3D%2216%22%20fill%3D%22%2358A9D7%22%2F%3E%0A%3Cpath%20d%3D%22M6.71429%2012.2852L14%204.9995L12.7143%203.71436L6.71429%209.71378L3.28571%206.2831L2%207.57092L6.71429%2012.2852Z%22%20fill%3D%22white%22%2F%3E%0A%3C%2Fsvg%3E");
}

.checkbox-off {
	background-image: url("data:image/svg+xml;charset=UTF-8,%3Csvg%20width%3D%2216%22%20height%3D%2216%22%20viewBox%3D%220%200%2016%2016%22%20fill%3D%22none%22%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%3E%0A%3Crect%20x%3D%220.75%22%20y%3D%220.75%22%20width%3D%2214.5%22%20height%3D%2214.5%22%20fill%3D%22white%22%20stroke%3D%22%2336352F%22%20stroke-width%3D%221.5%22%2F%3E%0A%3C%2Fsvg%3E");
}
	
</style></head><body><article id="1a3b87d1-0c7c-800e-bffa-fc8b0c80bb64" class="page sans"><header><h1 class="page-title">TEAMK</h1><p class="page-description"></p></header><div class="page-body"><p id="1a4b87d1-0c7c-800f-9176-e34e2dcaded7" class="">
</p><div id="1a4b87d1-0c7c-8042-a959-e86411849f00" class="column-list"><div id="1a4b87d1-0c7c-8013-b4a0-f1d7ea90df01" style="width:50%" class="column"><figure id="1a4b87d1-0c7c-80d6-b83d-fc06a9a82346" class="image"><a href="TEAMK%201a3b87d10c7c800ebffafc8b0c80bb64/22.png"><img style="width:224px" src="TEAMK%201a3b87d10c7c800ebffafc8b0c80bb64/22.png"/></a></figure></div><div id="1a4b87d1-0c7c-804b-bfce-ee2fa5e74d22" style="width:50%" class="column"><figure id="1a4b87d1-0c7c-8095-a56e-e57a9124f17d" class="image"><a href="TEAMK%201a3b87d10c7c800ebffafc8b0c80bb64/33.png"><img style="width:224px" src="TEAMK%201a3b87d10c7c800ebffafc8b0c80bb64/33.png"/></a></figure></div></div><div id="1a4b87d1-0c7c-80bb-99f1-e04cc67d3fcb" class="column-list"><div id="1a4b87d1-0c7c-80e7-b438-cc55d2ea6694" style="width:50%" class="column"><h3 id="1a4b87d1-0c7c-80a6-b9f0-f6cf4d667a1d" class="">🔹 <strong>Young Kim</strong> (웹 개발자)</h3><p id="1a4b87d1-0c7c-80bb-b100-f417e4dcbdfa" class="">💡 <em>“사용자 중심의 웹 개발을 지향하는 개발자”</em></p><ul id="1a4b87d1-0c7c-8095-b89c-e853b23f48bd" class="bulleted-list"><li style="list-style-type:disc"><strong>Github</strong>: <a href="https://github.com/kimyk0120">kimyk0120</a></li></ul><ul id="1a4b87d1-0c7c-8092-931b-d801cece830e" class="bulleted-list"><li style="list-style-type:disc"><strong>프로젝트 역할</strong>: 백엔드 개발, 데이터베이스 설계, 프론트엔드 개발</li></ul><ul id="1a4b87d1-0c7c-80f7-805b-ca087230f0c9" class="bulleted-list"><li style="list-style-type:disc"><strong>주요 기술 스택</strong>: <code>Java</code>, <code>Python</code></li></ul><ul id="1a4b87d1-0c7c-80c8-b96b-ca36a1e4a254" class="bulleted-list"><li style="list-style-type:disc"><strong>관심 분야</strong>: 서버 최적화, 분산 시스템, 자동화 시스템, DevOps</li></ul><p id="1a4b87d1-0c7c-80b6-b0cd-e3ac467b2548" class="">
</p></div><div id="1a4b87d1-0c7c-80dd-a03a-c89aa8f7e6cc" style="width:50%" class="column"><h3 id="1a4b87d1-0c7c-80fe-95cc-e47b1f045760" class="">🔹 <strong>Hyuk Min</strong> (AI 연구원)</h3><p id="1a4b87d1-0c7c-8095-a144-ee61a0584be4" class="">💡 <em>&quot;딥러닝 기반 AI 모델 연구 전문가”</em></p><ul id="1a4b87d1-0c7c-80bf-acdf-f777042111fb" class="bulleted-list"><li style="list-style-type:disc"><strong>Github</strong>: <a href="https://github.com/kwonhyeokmin">kwonhyeokmin</a></li></ul><ul id="1a4b87d1-0c7c-8098-9732-d0349dc7464c" class="bulleted-list"><li style="list-style-type:disc"><strong>프로젝트 역할</strong>: AI 모델 개발, 프론트엔드 구현, UI/UX 디자인</li></ul><ul id="1a4b87d1-0c7c-80d9-8326-c9512cc1bec3" class="bulleted-list"><li style="list-style-type:disc"><strong>주요 기술 스택</strong>: <code>Python</code>, <code>TensorFlow</code>, <code>Computer Vision (CV)</code></li></ul><ul id="1a4b87d1-0c7c-803a-9784-c9a8a25386fa" class="bulleted-list"><li style="list-style-type:disc"><strong>관심 분야</strong>: 딥러닝 최적화, AI 기반 영상 분석, 데이터 시각화</li></ul></div></div><p id="1a4b87d1-0c7c-8014-b97c-f90ecacd9c99" class="">
</p></div></article><span class="sans" style="font-size:14px;padding-top:2em"></span></body></html>

