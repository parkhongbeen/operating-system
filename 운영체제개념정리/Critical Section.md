## 임계영역(Critical Section)

### 임계 영역(Critical Section)과 크리티컬 섹션(임계 영역)

- 임계영역관 크리티컬 섹션은 똑같은 말이다.같은 말을 두번 반복하는 이유는 하나의 표현이 두 가지 의미로 사용되기 떄문이다.

### 임계영역(Critical Section)

- 원래 임계영역이란 둘 이상의 쓰레드가 동시에 실행될 경우 생길 수 있고 동시 접근 문제를 발생시킬 수 있는 **코드 블록**을 임계 영역이라고 한다.
- 동시 접근 문제가 발생한 메모리 공간(힙,데이터 영역)을 임계 영역이라고 하는게 아니라, 동시 접근 문제가 발생할 수 있는 우리가 짠 코드 블록을 임계영역이라고 한다.
- 임계 영역에 대한 정의를 있는 그대로 표현하면, 임계영역이란 베타적 접근이 요구되는 공유 리소스에 접근하는 코드 블록을 의미한다.