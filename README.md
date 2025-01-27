# ✏C언어에 대해 알아보자!
<br>

## 🌞 C언어의 등장
- 미국의 Bell 연구소의 Dennis M.Ritche가 UNIX 운영체제를 개발하기 위해 개발한 범용 `고수준` 언어
-  UNIX 운영체제 뿐만 아니라 각종 프로그래밍 언어의 컴파일러, 응용프로그램, 하드웨어 등 다양한 분야에서 다양한 소프트웨어가 개발되고 있음
<br>
<br>

## 😊 C언어의 장점
- 배우기 쉬움
- 구조화 되어있음
- 효율적으로 프로그램을 만들 수 있음
- 하드웨어 컨트롤, OS와의 직접 통신 등 저수준 활동을 처리 할 수 있음
- 다양한 컴퓨터 플랫폼에서 컴파일 가능
<br>
<br>

## 😢 C언어의 단점
- OS 별로 결과물을 만들기 때문에 OS 별로 작업을 따로 해줘야 함
- `메모리 관리`는 개발자가 직접 해야 함
<br>

## ❓ C언어를 사용하는 이유
- 시스템 개발 작업, 특히 `운영체제`를 구성하는 프로그램 개발에 사용됨
- 하드웨어와 관련된 작업, `메모리를 직접 관리`하는 작업 등과 같이 OS와 하드웨어를 직접 컨트롤 할 수 있음
- 기계어인 어셈블리 언어로 작성된 코드와 거의 비슷한 속도로 실행되는 코드를 생성 ➜ `시스템 개발 언어`로 채택
<br>
<br>

## 💫 C언어의 동작 원리
#### `소스코드(.c) ➜ 전처리기 ➜ 컴파일러(.obj, .o) ➜ 링크(.exe)`
1. 개발자가 `프로그램 코드(.c)`를 만듦
2. 개발자가 만든 코드를 전처리기에 의해 `전처리 명령어`가 먼저 처리 됨(소스코드의 일부분을 컴파일러가 인식할 수 있는 코드로 만들어줌)
3. 컴파일러가 전처리된 코드를 `컴퓨터나 OS가 인식할 수 있는 코드(.obj, .o)`로 만들어줌
4. 컴파일 되어 만들어진 파일은 `기계어로 변환되어 실행파일(.exe)로 만들어짐
  ➜ 해당 OS에서 실행하기 위해 필요한 여러가지 코드들을 추가해 하나의 실행파일로 만드는 작업


