# DJ-CDC 
## 프로젝트 개요
### 프로젝트 선정 배경
2022년 10월 15일의 [판교 데이터센터 화제사건](https://www.hani.co.kr/arti/society/society_general/1062797.html)은 판교의 클라우드 데이터센터에서 화제가 발생해 카카오와 네이버 관련된 서비스가 대거 중지되는 사건으로, 결과로 네이버, 카카오 등의 기업과 수많은 국민이 경제활동 제약, 메신저 사용 불가 등의 피해를 받았고 서비스 이용자들의 대거 이탈, 주가 급락 등 기업의 큰 손해로 이어진 사건입니다.
이 사건을 계기로 저희는 지속 가능한 데이터 운영의 중요성을 인식하고, 많은 사용자에게 안정적인 IT 서비스를 제공하는것에 기여하기 위해 DB 복제 솔루션의 시제품을 만드는 프로젝트를 선정하게 되었습니다.

### 프로젝트 목표
- 지속 가능한 데이터 운영의 중요성을 인식하고, 사용자에게 안정적인 IT 서비스를 제공합니다.
- 무중단 마이그레이션을 구현해보며, 다운타임이 없는 서비스 운영 솔루션을 제공합니다.
- 대용량의 데이터를 적은 비용으로 복제하고 운용하는 방법을 모색하며 연구하는 기회를 가집니다.

## Member
* 박경민 - 프로세스 제어 API, 프론트 개발 | <a href="https://github.com/kyungparkmin" target="_blank"><img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=GitHub&logoColor=white"/></a>
* 임동주 - 데이터 복제 개발 | <a href="https://github.com/DocRAID" target="_blank"><img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=GitHub&logoColor=white"/></a>
* 이재성 - 인프라(aws), 데이터 적용 | <a href="https://github.com/showbon218" target="_blank"><img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=GitHub&logoColor=white"/></a>

## 사용 기술
|기술|사용분야|선정이유|기타|
|-----|-----|-----|-----|
|KafKa|데이터 분산 파이프라인|프로그램 규모 확장 용이, Queue 구조||
|C++|데이터 복제|데이터 처리 효율 개선|버전관리: Vcpkg, 빌드: Cmake|
|Python|QA, 데이터 적용|빠른 테스트에 용이||
|AWS|인프라 구축|솔루션 적용 환경 구성|E2C|
|NodeJS|대시보드, 프로세스 관리 API|Web 환경에서 프로세스 관리가 쉽게 가능함, 접근성 용이||
|PostgreSQL|SourceDB 환경|대중적으로 쓰이는 DBMS|Logical Decode|
|MySQL|TargitDB 환경|대중적으로 쓰이는 DBMS||
