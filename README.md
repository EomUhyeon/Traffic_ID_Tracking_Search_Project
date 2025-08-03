# Traffic_ID_Tracking_Search_Project
- 2025/08/03


Traffic_ID_Tracking_Search_Project/
│
├── frontend/                          # 사용자 화면 서비스 (포트 3000)
│   ├── Dockerfile                    # Next.js 컨테이너 빌드 설정
│   ├── package.json                  # Node.js 의존성 (next, react, typescript)
│   ├── next.config.js                # Next.js 프레임워크 설정
│   ├── tsconfig.json                 # TypeScript 컴파일러 설정
│   └── src/                          # 소스코드 (실시간 볼륨 마운트)
│       └── app/                      # Next.js App Router 구조
│           ├── layout.tsx            # 기본 HTML 레이아웃
│           └── page.tsx              # "Hello World" 메인 페이지
│
├── backend/                           # API 서버 서비스 (포트 5001)
│   ├── Dockerfile                    # Python 컨테이너 빌드 설정
│   ├── main.py                       # 메인 서버 코드 (2줄)
│   └── requirements.txt              # Python 의존성 (현재 비어있음)
│
├── triton/                            # AI 추론 서버 (포트 8000-8002)
│   ├── Dockerfile                    # NVIDIA Triton 컨테이너 설정
│   └── models/                       # AI 모델 저장소 (현재 비어있음)
│
├── mariadb/                           # 데이터베이스 저장소 (포트 3306)
│   ├── data/                         # 실제 데이터베이스 파일들
│   └── log/                          # 데이터베이스 로그 (현재 비어있음)
│
├── README.md                          # 프로젝트 기본 정보
├── .env                               # 환경 변수 (DB 비밀번호 등)
├── .gitignore                         # Git 제외 설정
├── docker-compose.yml                 # 4개 서비스 오케스트레이션 설정
└── memo.txt                           # Docker 명령어 모음집
