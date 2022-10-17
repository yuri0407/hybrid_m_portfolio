[포트폴리오 바로가기](https://yuri0407.github.io/hybrid_m_portfolio/)
[포트폴리오 바로가기(Netlify)](https://hybrid-m-portfolio.netlify.app/)

# 사용한 프레임워크

## 1. Bootstrap

![image](https://user-images.githubusercontent.com/94339489/196033562-9ee8a9ab-ab5a-41e5-a94e-e9f3df23daa4.jpg)

Bootstrap은 더 빠르고 쉬운 웹 개발을 위한 무료 프론트엔드 프레임워크입니다.
Bootstrap에는 타이포그래피, 양식, 버튼, 테이블, 탐색, 모달, 이미지 캐러셀 및 기타 여러 가지를 위한 HTML 및 CSS 기반 디자인 템플릿과 선택적 JavaScript 플러그인이 포함되어 있습니다.
또한 Bootstrap은 반응형 디자인을 쉽게 만들 수 있는 기능을 제공합니다.


#### 이 프레임워크를 사용한 부분
![image](https://user-images.githubusercontent.com/94339489/196012762-5b332816-c5a0-41d3-ab97-4454990938df.jpg)
![image](https://user-images.githubusercontent.com/94339489/196012791-ad2ace91-fc35-4ebc-969d-a1a7caaecd7c.jpg)

## 2. Bulma

![image](https://user-images.githubusercontent.com/94339489/196033574-d6081a8f-b5fb-41f8-be1d-b87676e4b178.jpg)

Flextbox 기반의 무료, 오픈소스 CSS framework이다.

### 장점
* 가볍다. JavaScript 없이 CSS만을 사용하기 때문에 엄청 가볍다.
* CSS3의 최신 기술들을 활용하기 때문에 상황에 따라 굉장히 편리하다.
* Learning curve가 낮은 편이다. Element에 class를 추가하는 형태로 동작하기 때문에 익히고 적용하기가 쉽다.
* Customize가 쉽다. 애초에 customize를 많이 염두에 둔 듯 하다. 변수 선언을 통해 customize할 수 있다.
* Bulma가 정해놓은 class를 지정해야지만 style이 적용되기 때문에 내가 적용한 다른 CSS를 오염시키지 않는다. 가장 마음에 들었던 장점이다. Bulma에서 제공하는 class를 적용시키지 않으면, 내 HTML 문서는 전혀 변하지 않는다. 이 덕분에 custom은 더 쉬워지고, CSS error를 발견하기 쉬워진다.
* Bootstrap보다 사용자가 적기 때문에, 참신한 느낌을 준다. 이미 사용자들은 Bootstrap으로 만든 웹사이트에 익숙해졌고, 개발자들은 참신함을 주기 위해 Bootstrap의 느낌을 빼는데 시간을 들인다. Bulma로 만든 웹사이트는 아직까지는 기시감을 주지 않는다.

### 단점
* JavaScript 없이 동작하기때문에 한계가 있다. 아직까지는 CSS만으로 역동적인 frontend를 만드는데 제약이 존재한다.
* 브라우저 호환성이 낮다. JavaScript를 사용하지 않았고 CSS3의 최신 기술들을 활용하기 때문에 100% 호환되지 않는 브라우저들이 존재한다. 이는 구형 브라우저 사용이 많은 한국에서는 특히 심각한 단점이다.
* 한국어 가이드 문서를 구하기 어렵다.

#### 이 프레임워크를 사용한 부분
![image](https://user-images.githubusercontent.com/94339489/196012799-e30d0395-0ffc-420e-ad8b-7fa84408dbab.jpg)
![image](https://user-images.githubusercontent.com/94339489/196012819-52c59d99-97e8-42e6-8f43-d7e93c1f5e26.jpg)


## 3. Pure.css

![image](https://user-images.githubusercontent.com/94339489/196033583-01db6082-c2ff-4573-82a4-5a026f851c55.jpg)

### 최소한의 공간을 차지하는 CSS

Pure은 매우 작습니다. 전체 모듈 세트는 3.7KB *로 축소되고 gzip으로 압축 됩니다.
모바일 장치를 기준으로 두고 제작되었기 때문에 파일 크기를 작게 유지하는 것이 중요했으며 CSS의 모든 라인이 신중하게 고려되었습니다.
이러한 모듈의 하위 집합만 사용하기로 결정하면 공간을 더 많이 절약할 수 있습니다.

#### 이 프레임워크를 사용한 부분
![image](https://user-images.githubusercontent.com/94339489/196012843-cd57b674-a222-448b-8f9e-6eef834c8317.jpg)


## 4. UIKit

![image](https://user-images.githubusercontent.com/94339489/196033597-2a5e992d-90ef-4354-b429-53b379417625.jpg)

### 패키지 내용

압축 파일에는 시작하는 데 필요한 컴파일된 CSS 및 JavaScript 파일이 포함되어 있습니다.
나중에 UIkit을 직접 설치 및 컴파일 하고 고유한 UIkit 테마를 만들 수도 있습니다.

### UIKit 자동 완성

UIkit의 사용은 Sublime Text 또는 Atom 과 같은 견고한 코드 편집기가 있는 경우 가장 잘 작동합니다.
더 효율적으로 사용하려면 선호하는 IDE 또는 코드 편집기에 대한 자동 완성 플러그인 중 하나를 설치하는 것이 좋습니다.
이렇게 하면 모든 UIkit 클래스와 마크업을 찾아 입력할 필요가 없으므로 많은 시간을 절약할 수 있습니다.

### 브라우저 지원

많은 브라우저가 롤링 릴리스 전략으로 이동함에 따라 특정 버전에 대한 브라우저 지원을 고정하는 것이 최근 몇 년 동안 약간 까다로워졌습니다.
간단히 말해서 UIkit은 거의 모든 최신 브라우저에서 작동합니다.


#### 이 프레임워크를 사용한 부분
![image](https://user-images.githubusercontent.com/94339489/196013083-c472843f-1f96-4d31-b188-66a92f0fe320.jpg)
![image](https://user-images.githubusercontent.com/94339489/196013088-b3f375d1-4352-4de1-81aa-08c03981277f.jpg)
