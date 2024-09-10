## 이세현(Sehyeon Lee)

#### Network Developer 

**Contact**  
email - lsh49516333@gmail.com <br>
github - https://github.com/Seeeh-Leee <br>
naver blog - [https://blog.naver.com/cocoder_](https://blog.naver.com/cocoder_) <br>
velog - https://velog.io/@cocoder123/posts <br>

**About Me**
> 오늘보다 더 나은 내일의 개발자
- **한동대학교 전산전자 공학부 컴퓨터공학과를 졸업했습니다. 네트워크 개발자/클라우드 아키텍쳐가 되고 싶은 이세현 입니다.**
  

<br><br><br>
# **Project Abstract**
| 기간 | 프로젝트 명 | 내용     |
|:----|:---------|:--------|
| 2022.04.01 – 2023.12.14 | 파운틴 코드 기반 피어 투 피어 파일 공유 프로그램 | FEC기술의 한 종류인 Fountain Code를 P2P 파일 공유에 활용한 블록체인 블록 전송, 파일 공유 프로그램. 등록번호 C-2023-059968|
| 2022.06.01 - 2023.06.31 | 블록체인을 위한 devp2p 기반의 저지연 블록 전송 프로토콜 | FEC기반 블록 전송 기술과 QUIC 프로토콜을 이더리움에 적용한 프로토콜 개발. |
| 2023.03.01 - 2023.06.31 | 스케치 퀴즈 | 2인 1조로 진행한 프로젝트. C++, Boost Asio, OpenCV를 활용하여 '스케치퀴즈' 게임을 PC로 구현. 사용자간 실시간 네트워크 통신과 그림 데이터 처리.|
| 2019.11.21 - 2019.11.22 | FingerPrintApp | 폴란드 AMU에서 Mobile Security 수업에서 진행한 프로젝트. 지문인식을 적용해 보안을 강화한 노트 작성 앱. |
| 2023.01.26 - 2023.01.28 | FAT32 파일시스템 분석기 | 파일 시스템을 주제로 저수준의 시스템 구성요소를 분석하고 이미지 포렌식을 실습. |



---

# **Projects Details**

## Fountain Code 기반 P2P 파일 공유 프로그램
> FEC기술의 한 종류인 Fountain Code를 P2P 파일 공유에 활용한 블록체인 블록 전송, 파일 공유 프로그램.

- 개발기간 : 2022.04.01 – 2023.12.14
- 역할 : FEC/다중경로 코드 블록체인에 적용, 성능 테스트
- Language : golang
- Skill : Linux, AWS E2C, shell script, github
- [한국 저작권 협회 저작권 등록 번호 : C-2023-059968]
- 네트워크 환경이 불안정해 데이터 재전송이 불가능한 경우를 대비해 FEC/다중경로 기능을 적용하여 블록 전송과 파일 공유를 할 수 있는 프로그램입니다. 프로그램의 성능 테스트를 위해 AWS EC2, VPC를 활용했습니다. 5개의 리전에 EC2를 생성 후 가각 인스턴스 끼리 통신이 가능하도록 환경을 구성했습니다.
---

## 블록체인을 위한 devp2p 기반의 저지연 블록 전송 프로토콜
> FEC기반 블록 전송 기술과 QUIC 프로토콜을 이더리움에 적용한 프로토콜.

- 개발기간 : 2022.06.01 - 2023.06.31
- 역할 : 코드 분석, 기능 테스트
- Language : golang
- Skill : Linux, AWS E2C, shell script, github
- 한국 저작권 협회 저작권 등록 번호 : C-2023-059968

- 네트워크 환경이 불안정해 데이터 재전송이 불가능한 경우를 대비해 FEC/다중경로 기능을 적용하여 블록 전송과 파일 공유를 할 수 있는 프로그램입니다. TCP 기반의 블록 전송 프로그램을 QUIC 기반의 블록 전송 프로토콜로 변환 했습니다. 프로그램의 성능 테스트를 위해 AWS EC2, VPC를 활용했습니다. 5개의 리전에 EC2를 생성 후 가각 인스턴스 끼리 통신이 가능하도록 환경을 구성했습니다.


---
## Sketch Quiz
> 소켓 프로그래밍과 OpenCV를 활용한 그림 퀴즈.

- 개발기간 : 2022.06.01 - 2023.06.31
- 역할 : 실시간 데이터 처리, 비동기식 데이터 처리, 사용자간 소통 화면 구성
- Language : C
- Skill : Socket Programming, OpenCV, Tcp/ip
- Github link : https://github.com/SuhyunRim118/SketchQuiz

- 출제자는 제시어를 그림판에 그리고, 응시자는 제시어를 맞추는 게임입니다. Multi Thread 사용하여 그림 데이터와 제시어 데이터를 구분했습니다.

---
## FingerPrintApp
> 폴란드 AMU에서 Mobile Security 수업에서 진행한 프로젝트. 지문인식을 적용해 보안을 강화한 노트 작성 앱.

- 개발기간 : 2019.11.21 - 2019.11.22
- 역할 : 노트 앱, 지문 인식 기능
- Language : Kotlin
- Skill : Android Studio
- Github link : https://github.com/Seeeh-Leee/FingerPrintApp

- 사용자가 작성한 데이터를 비밀번호와 지문인식을 통해 보호하는 노트 앱입니다. AES256 method와 EncryptedSharedPreferences function을 활용하여 보안을 강화했습니다.

---
## FAT32 파일시스템 분석기
> 파일 시스템을 주제로 저수준의 시스템 구성요소를 분석하고 이미지 포렌식 실습, 파일시스템 분석기 프로그램 구현.

- 개발기간 : 2023.01.26 - 2023.01.28
- Language : C++
- Skill : docker, vim, linux, fat32
- Github link : https://github.com/Seeeh-Leee/fat32_src

- 저수준 파일 시스템 구조 분석을 통한 고급 프로그래밍 실습 캠프에서 파일시스템 분석기 프로그램을 만들었습니다. Fat32 덤프 이미지에서 삭제된 파일을 복원할 수 있는 프로그램입니다.

