## HTTP와 HTTPS의 차이점
1. 보안: HTTPS는 SSL/TLS 암호화를 사용하여 데이터를 암호화하지만, HTTP는 평문으로 데이터를 전송합니다.
2. 포트: HTTP는 80번 포트를, HTTPS는 443번 포트를 사용합니다.
3. URL: HTTP는 "http://"로, HTTPS는 "https://"로 시작합니다.
4. 데이터 무결성: HTTPS는 데이터 변조를 방지할 수 있지만, HTTP는 그렇지 않습니다.
5. 검색 엔진 최적화: HTTPS는 검색 순위 향상에 도움됩니다.

## iOS에서의 보안 통신 방법
1. HTTPS 사용: 모든 네트워크 통신에 HTTPS를 사용합니다.
2. 인증서 고정(Certificate Pinning): 신뢰할 수 있는 인증서만 허용하도록 구현합니다.
3. ATS(App Transport Security) 활용: iOS의 ATS를 사용하여 보안 연결을 강제합니다.
4. 데이터 암호화: 민감한 데이터는 전송 전에 추가로 암호화합니다.
5. JWT(JSON Web Token) 인증: API 요청의 인증 및 권한 부여에 JWT를 사용합니다.
6. 네트워크 보안 구성: iOS의 Network Security Configuration 기능을 활용하여 앱의 네트워크 보안 설정을 구성합니다.
