# Brute Force
암호화된 데이터를 해독하거나 시스템에 접근하기 위해 가능한 모든 조합을 체계적으로 시도하는 해킹 기법

무차별 대입

## 특징
- 단순하지만 강력함

- 자동화된 스크립트나 도구를 사용

- 암호화 방식에 따라 난이도가 차이남

## 유형
1. 단순 Brute Force

    - 모든 가능한 문자 조합을 하나씩 시도함

    - 비밀번호 길이가 짧고 단순할수록 효과적
  
2. 사전 공격(Dictionary Attack)

    - 일반적으로 많이 사용되는 비밀번호 목록을 기반으로 시도

3. 하이브리드 공격(Hybrid Attack)

    - 사전 공격에 Brute Force를 결합한 방식

4. 크리덴셜 스터핑(Credential Stuffing)

    - 이전에 유출된 사용자 이름과 비밀번호를 재사용하여 로그인 시도

    - 사용자가 여러 계정에서 동일한 비밀번호를 사용하는 경우에 효과적

## 방어 방법
1. 강력한 비밀번호 사용
   
2. 계정 잠금 설정
   
3. 2단계 인증(2FA)
   
4. 캡차(CAPTCHA) 사용
   
5. 비밀번호 해시화 및 솔트 처리