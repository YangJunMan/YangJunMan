# 양준혁 (Yang Junhyeok)

<p align="left">
  <b>현업의 맥락을 듣고 자동화로 연결하는 엔지니어입니다.</b><br>
  비IT 실무자의 눈높이에서 소통하며 데이터 기준을 정립하고, AI 파이프라인과 자동화 스크립트로 반복 운영 업무를 해결합니다.
</p>

<p align="left">
  <a href="https://www.yangjunman.com/resume"><img src="https://img.shields.io/badge/Resume-이력서_바로가기-2563eb?style=for-the-badge&logo=googledocs&logoColor=white" alt="Resume"></a>
  <a href="https://www.yangjunman.com/lab"><img src="https://img.shields.io/badge/Lab-실험실_둘러보기-059669?style=for-the-badge&logo=flask&logoColor=white" alt="Lab"></a>
  <a href="https://www.yangjunman.com/blog"><img src="https://img.shields.io/badge/Blog-기술_블로그-475569?style=for-the-badge&logo=blogger&logoColor=white" alt="Blog"></a>
  <a href="https://github.com/YangJunMan/service-uptime-monitor"><img src="https://img.shields.io/badge/Status-All_Services_Live-10b981?style=for-the-badge&logo=statuspage&logoColor=white" alt="Uptime Status"></a>
</p>

---

## 📌 어떤 것을 먼저 보면 좋을까요? (Quick Guide)

방문해 주셔서 감사합니다! 목적에 따라 아래 링크를 먼저 살펴보시면 저의 경험과 기술 역량을 가장 빠르게 파악하실 수 있습니다.

| 바로가기 | 설명 | 주요 확인 포인트 |
| :--- | :--- | :--- |
| 📄 **[이력서 (Resume)](https://www.yangjunman.com/resume)** | 엔지니어링 경력, 프로젝트 STAR 기록 | 클레슨 데이터 거버넌스, 강의자료 자동화, 산학협력 문서 자산화 |
| 🧪 **[실험실 (Live Showcase)](https://www.yangjunman.com/lab)** | 직접 기획·구축해 상시 운영 중인 라이브 서비스 | 홈서버(jammy-sub) 회의록 AI 파이프라인, Windows AD 랩, TokenBench, 경매 지도 웹 |
| 📚 **[기술 블로그 (Blog)](https://www.yangjunman.com/blog)** | 인프라 운영과 문제 해결 회고 (30여 편) | 온프레미스 권한 체계 분석, Vercel 서버리스 타임아웃 트러블슈팅, 실패와 한계 솔직 기록 |

---

## 🚀 대표 프로젝트 (Featured Projects)

### 1. [Token Savings Benchmark](https://github.com/YangJunMan/claude-code-token-savings-benchmark)
- **개요**: AI 코딩 도구의 토큰 절약 프롬프트들이 실제 비용을 줄여주는지 GitHub Actions에서 **130회 자동 반복 측정**한 벤치마크.
- **성과**: 기본 변동폭(±33.7%)을 입증하여 마케팅식 과장 뒤의 '실질 절약 효과 미확인' 결론을 데이터로 도출. 조직의 불필요한 설정 도입 비용 방지.
- **스택**: GitHub Actions, Python, Web Dashboard (GitHub Pages)

### 2. [Windows Server AD 랩 (하이브리드 계정 체계)](https://lab.yangjunman.com/winlab/)
- **개요**: 제조 기업 근무 당시 체감했던 부서별 파일 서버 권한 격리와 보안 반출 절차를 Hyper-V 가상화 및 Windows Server 2025 환경으로 직접 재현.
- **성과**: 조직 단위(OU), 보안 그룹(AGDLP 원칙), GPO 드라이브 맵 정책을 통해 웹 브라우저에서 역할별 권한 격리 및 반출 승인을 직접 체험할 수 있는 포털 상시 가동.
- **스택**: Windows Server 2025, AD DS, GPO, Hyper-V, Cloudflare Tunnel

### 3. [회의록 만들기 (로컬 AI 음성 전사 & 요약 파이프라인)](https://lab.yangjunman.com/minutes/)
- **개요**: 홈서버(Ubuntu 24.04, RTX 2080 SUPER)에서 Whisper 모델과 LLM을 연동해 브라우저 녹음 즉시 회의록을 생성하고 Confluence로 자산화하는 무개입 파이프라인.
- **성과**: 회의록 작성 수작업 공수 0분 단축, 24시간 후 음성 데이터 자동 파기로 프라이버시 보호.
- **스택**: Whisper, Python systemd 데몬, Confluence API, Cloudflare Tunnel

### 4. [내 집 찾기 (Search Auction - 법원 부동산 경매 시각화)](https://github.com/YangJunMan/search_auction)
- **개요**: 법원 부동산 경매 물건의 유찰 횟수, 감정가 대비 비율, 역세권 반경을 지도 위에서 실시간 필터링할 수 있는 풀스택 웹 서비스.
- **성과**: Vercel Serverless Function 10초 타임아웃 문제를 `maxDuration: 60`, 메모리 1024MB 확장 및 예외 로깅 세분화로 해결.
- **스택**: Next.js, Vercel Serverless, Puppeteer-core, Kakao Maps API

### 5. [Service Uptime Monitor](https://github.com/YangJunMan/service-uptime-monitor)
- **개요**: 상시 서비스 중인 블로그, 랩, 홈서버 인스턴스를 **5분 주기 크론(GitHub Actions)**으로 실시간 헬스체크하고 장애 시 GitHub Issue로 자동 통보하는 모니터링 시스템.
- **성과**: 전 서비스 가동률 100% 투명 공개 및 실시간 상태 보드 운영.

---

## 🛠️ 보유 기술 스택 (Tech Stack)

- **인프라 & 시스템**: Linux (`RHCSA 취득`), Windows Server 2025 파일 서버 및 AD DS, k3s, Ansible, Tailscale, Ubuntu Server
- **협업 & 문서 거버넌스**: Confluence, GitHub Actions, Git, Markdown, 런북/매뉴얼 자산화
- **자동화 & 웹**: Python, PowerShell, Next.js, Node.js, Vercel Serverless
- **AI 도구 & 엔지니어링**: Claude Code, OpenAI Codex, Gemini CLI, Whisper 로컬 서빙

---

## 🎯 핵심 원칙 (Core Values)

1. **고객 (Customer)**: 결과물의 최종 평가자는 사용하는 현업 동료입니다. 기술을 강요하기보다 비IT 실무자의 눈높이에 맞춘 가이드를 정립합니다.
2. **기록 (Documentation)**: 기록되지 않은 일은 없던 일이 되고, 판단은 추측이 아닌 숫자로 합니다. (산학 연구 Confluence 100% 인계)
3. **실행력 (Action)**: 반복되는 비효율은 생각에 머무르지 않고 직접 만든 스크립트와 상시 가동 서비스로 해결합니다.

---

<p align="center">
  <sub>© 2026 Yang Junhyeok · Contact: <a href="mailto:tfea0021@gmail.com">tfea0021@gmail.com</a></sub>
</p>
