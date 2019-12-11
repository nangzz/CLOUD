## 1. AWS Ec2 서버 만들기

  ### 1.1 AMI os 이미지 선택
  ![aws](/assets/images/duck.jpg)
  ### 1.2 서버 사양 선택(cpu, 메모리, 가격 등)
  ### 1.3 인스턴스 세부 정보 구성
        - 인스턴스 개수, 네트워크 설정 등
  ### 1.4 스토리지 추가
  ### 1.5 태그 추가(옵션)
  ### 1.6 보안설정
         - ssh 접속 설정, 보안 그룹등
         - 키페어 생성 or 지정
  ### 1.7 끝!

## 2. Window 콘솔/터미널 창에서 서버 Ec2서버 접속하기
 
 ```
 $ ssh -i test.pem(PEM키 위치) ec2-user@IP주소
 ```
 ### 2.1 서버에 필요한 패키지 설치
 ```
 $ sudo yum update
 ```
 