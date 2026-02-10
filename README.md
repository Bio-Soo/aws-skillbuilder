# AWS 자격증 공부 가이드

AWS Cloud Practitioner와 AI Practitioner 자격증 준비를 위한 체계적인 학습 자료입니다.

🌐 **웹사이트:** https://bio-soo.github.io/aws-skillbuilder/

## 📚 포함된 자격증

### 1. AWS Certified Cloud Practitioner (CLF-C02)
- **난이도**: 기초
- **시험 시간**: 90분
- **문항 수**: 65문항 (50개 채점 + 15개 미채점)
- **합격 점수**: 700/1000
- **시험 비용**: $100 USD

AWS 클라우드의 기본 개념, 서비스, 보안, 아키텍처, 가격 및 지원에 대한 전반적인 이해를 검증합니다.

### 2. AWS Certified AI Practitioner (AIF-C01)
- **난이도**: 기초
- **시험 시간**: 120분
- **문항 수**: 85문항 (65개 채점 + 20개 미채점)
- **합격 점수**: 700/1000
- **시험 비용**: $100 USD
- **출시일**: 2024년 6월 (신규)

AWS의 AI/ML 서비스와 생성형 AI에 대한 기본 지식을 검증합니다.

## 🚀 주요 기능

### ✅ 체계적인 학습 자료
- 시험 도메인별로 정리된 상세 내용
- 공식 AWS 시험 가이드 기반
- 최신 2024-2026 시험 정보 반영

### ✅ 실전 연습 문제
- Cloud Practitioner: 8개 연습 문제
- AI Practitioner: 8개 연습 문제
- 상세한 정답 해설 포함

### ✅ 서비스 비교 및 선택 가이드
- 유사 서비스 간 차이점 명확히 비교
- 상황별 최적 서비스 선택 가이드
- 실전 문제 패턴 분석

### ✅ 학습 팁 및 전략
- 효과적인 학습 로드맵
- 시험 당일 전략
- 무료 학습 리소스 안내
- FAQ

### ✅ 사용자 친화적 디자인
- 깔끔하고 가독성 높은 UI
- 반응형 디자인 (모바일, 태블릿, 데스크톱)
- AWS 공식 컬러 테마

## 📖 학습 내용

### Cloud Practitioner (CLF-C02)
1. **클라우드 개념 (24%)**
   - 클라우드 컴퓨팅의 이점
   - AWS Well-Architected Framework
   - 클라우드 경제성

2. **보안 및 규정 준수 (30%)**
   - AWS 공동 책임 모델
   - IAM 및 보안 서비스
   - 규정 준수 프로그램

3. **클라우드 기술 및 서비스 (34%)**
   - 컴퓨팅 (EC2, Lambda, ECS 등)
   - 스토리지 (S3, EBS, EFS 등)
   - 데이터베이스 (RDS, DynamoDB 등)
   - 네트워킹 (VPC, CloudFront, Route 53 등)

4. **결제, 가격 및 지원 (12%)**
   - 가격 모델 (온디맨드, 예약, 스팟 등)
   - 비용 관리 도구
   - 지원 플랜

### AI Practitioner (AIF-C01)
1. **AI 및 ML의 기초 (20%)**
   - AI/ML 기본 개념
   - 학습 유형 (지도, 비지도, 강화)
   - ML 파이프라인

2. **생성형 AI의 기초 (24%)**
   - Foundation Models
   - 프롬프트 엔지니어링
   - RAG vs Fine-tuning

3. **AWS AI/ML 서비스 응용 (28%)**
   - Amazon Bedrock
   - Amazon SageMaker
   - AI 서비스 (Rekognition, Comprehend 등)

4. **책임 있는 AI 지침 (14%)**
   - AI 윤리 및 공정성
   - 편향 감지 및 완화
   - Guardrails

5. **보안, 규정 준수 및 거버넌스 (14%)**
   - AI 보안 모범 사례
   - 데이터 보호
   - 모델 거버넌스

## 🎯 학습 팁

1. **순차적 학습**: 각 도메인을 순서대로 학습하세요
2. **반복 학습**: 핵심 키워드와 서비스 비교는 여러 번 복습하세요
3. **실습**: AWS Free Tier를 활용하여 직접 서비스를 사용해보세요
4. **모의고사**: AWS Skill Builder에서 공식 연습 문제를 풀어보세요
5. **시간 관리**: 실전처럼 시간을 재며 문제를 풀어보세요

## 🔗 유용한 링크

- [AWS Skill Builder](https://skillbuilder.aws/) - 무료 디지털 교육
- [AWS 공식 시험 가이드](https://aws.amazon.com/certification/) - 시험 정보
- [AWS Free Tier](https://aws.amazon.com/free/) - 무료 실습 환경
- [AWS 백서](https://aws.amazon.com/whitepapers/) - Well-Architected Framework 등

## 📱 웹사이트 구조

```
aws-skillbuilder/
├── index.html              # 홈페이지
├── cloud-practitioner.html # Cloud Practitioner 가이드
├── ai-practitioner.html    # AI Practitioner 가이드
├── study-tips.html         # 학습 팁 및 전략
├── styles.css              # 스타일시트
└── README.md               # 이 파일
```

## 🚀 로컬에서 실행하기

```bash
# 저장소 클론
git clone https://github.com/Bio-Soo/aws-skillbuilder.git
cd aws-skillbuilder

# 간단한 HTTP 서버 실행 (Python 3)
python -m http.server 8000

# 또는 Node.js 사용
npx http-server
```

브라우저에서 `http://localhost:8000` 접속

## 📄 라이선스

이 프로젝트는 학습 목적으로 제작되었습니다.

## 🤝 기여

개선 사항이나 추가 내용이 있다면 자유롭게 기여해주세요!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📞 문의

질문이나 제안사항이 있으시면 Issue를 생성해주세요.

---

**행운을 빕니다! 🎉**

*Last Updated: 2024년 2월*
