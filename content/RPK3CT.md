---
publish: true
---

# RPK3CT

---

RPK3CT는 Root Permission Kernel Control Command Console Terminal의 약자로, 현실의 커널과 연결되어 명령어를 통해 세상을 조작할 수 있는 콘솔 단말기이다.

## 외형

---

![[Assets/Media/RPK3CT/IMG-20260428152033893.webp]]

외형은 마치 90년대 단말기와 같이 생겼다. 키패드로 명령어를 입력할 수 있다. 인터폰으로는 스스로를 신, 우주라 칭하는 자와 소통할 수 있다.

## 명령어 형식

---

### 객체와 속성 선언

---

모든 구성 요소는 객체로 정의된다. 원자 하나부터 거대한 은하계까지 각각의 고유한 가변 길이 UUID를 부여 받는다. 4bit 부터 시작한 것으로 추정되며, 현재 형식은 512bit UUID이다.

UUID와 다른, 사용자의 언어로 추상화된 객체 경로 시스템이 존재한다. 해당 추상 객체 경로에는 앞에 `$`를 붙여 사용한다.

**예시**

- `$Earth.Atmoshpere.Oxygen.Density = 25%`
