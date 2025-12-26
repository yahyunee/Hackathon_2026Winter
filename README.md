# 2026 Neuro-AI Grand Hackathon 웹사이트

🧠 2026 Neuro-AI Grand Hackathon 공식 웹사이트 - 5개 연구실과 40명의 연구자가 함께하는 뇌과학 협업 스프린트

**웹사이트:** https://yahyunee.github.io/Hackathon_2026Winter

---

## 📚 소개

2026 Neuro-AI Grand Hackathon의 공식 웹사이트입니다. 최첨단 뇌과학 및 AI 연구에 집중하는 5박 6일간의 집중적인 협업 연구 스프린트입니다.

### 주요 기능
- 🌐 **다국어 지원:** 한국어 및 영어 콘텐츠 완벽 지원
- 📖 **종합 가이드:** 해커톤이란 무엇인지, 준비 요구사항, 모범 사례
- 🔬 **연구 프로젝트:** 10개 팀의 연구 주제 상세 정보
- 📚 **튜토리얼:** 데이터 전처리, GPU 설정 등 기술 가이드
- 🎨 **반응형 디자인:** 데스크톱, 태블릿, 모바일 모두 지원

---

## 🏗️ 구조

```
Hackathon_2026Winter/
├── _config.yml           # Jekyll 설정
├── _layouts/             # HTML 템플릿
│   └── default.html      # 네비게이션이 있는 메인 레이아웃
├── assets/
│   └── css/
│       └── style.css     # 커스텀 스타일링
├── en/                   # 영어 콘텐츠
│   ├── index.md          # 홈페이지
│   ├── overview.md       # 해커톤이란?
│   ├── projects.md       # 연구 프로젝트
│   └── tutorials.md      # 튜토리얼 & 가이드
├── kr/                   # 한국어 콘텐츠
│   ├── index.md          # 홈페이지
│   ├── overview.md       # 해커톤이란?
│   ├── projects.md       # 연구 프로젝트
│   └── tutorials.md      # 튜토리얼 & 가이드
└── 해커톤-2026-arpa.pdf   # 참고 문서
```

---

## 🚀 시작하기

### 사전 요구사항
- Git
- Ruby (버전 2.7 이상)
- Jekyll

### 로컬 개발

1. **저장소 복제**
   ```bash
   git clone https://github.com/yahyunee/Hackathon_2026Winter.git
   cd Hackathon_2026Winter
   ```

2. **Jekyll 설치** (아직 설치하지 않은 경우)
   ```bash
   gem install bundler jekyll
   ```

3. **Gemfile 생성**
   ```bash
   echo 'source "https://rubygems.org"
   gem "github-pages", group: :jekyll_plugins' > Gemfile
   ```

4. **의존성 설치**
   ```bash
   bundle install
   ```

5. **로컬 서버 실행**
   ```bash
   bundle exec jekyll serve
   ```

6. **사이트 확인**
   - 브라우저에서 `http://localhost:4000/Hackathon_2026Winter/` 접속

---

## 🌐 GitHub Pages 배포

### 초기 설정

1. **GitHub에 새 저장소 생성**
   - 저장소 이름: `Hackathon_2026Winter`
   - Public으로 설정
   - README로 초기화하지 않음 (이미 있음)

2. **원격 저장소 추가 및 푸시**
   ```bash
   git remote add origin https://github.com/yahyunee/Hackathon_2026Winter.git
   git add .
   git commit -m "Initial commit: 2026 Neuro-AI Hackathon website"
   git branch -M main
   git push -u origin main
   ```

3. **GitHub Pages 활성화**
   - 저장소 Settings → Pages로 이동
   - Source: Deploy from a branch
   - Branch: `main` / `(root)`
   - Save 클릭

4. **몇 분 대기**
   - 사이트가 다음 주소에서 사용 가능합니다: `https://yahyunee.github.io/Hackathon_2026Winter/`

### 사이트 업데이트

```bash
# 변경 사항 작성
git add .
git commit -m "Update content"
git push
```

GitHub Pages가 자동으로 변경 사항을 재빌드하고 배포합니다.

---

## 📝 콘텐츠 업데이트

### 팀 정보 추가
`/en/projects.md` 또는 `/kr/projects.md`를 편집하여 실제 팀 리더 이름과 연구 세부 사항으로 팀 카드를 업데이트하세요.

### 일정 업데이트
`/en/overview.md` 및 `/kr/overview.md`의 일정 표를 특정 날짜 및 장소로 수정하세요.

### 튜토리얼 추가
`/en/tutorials.md` 또는 `/kr/tutorials.md`에 새로운 튜토리얼 섹션을 추가하세요.

---

## 🎨 커스터마이징

### 색상 변경
`/assets/css/style.css`를 편집하고 CSS 변수를 수정하세요:

```css
:root {
    --primary-color: #2c3e50;      /* 메인 네비게이션 색상 */
    --secondary-color: #3498db;     /* 강조 색상 */
    --accent-color: #e74c3c;        /* 하이라이트 색상 */
}
```

### 네비게이션 수정
`/_layouts/default.html`을 편집하여 네비게이션 링크를 추가하거나 제거하세요.

---

## 📋 해커톤 정보

### 행사 상세
- **일시:** 2026년 1월 18일 - 23일
- **장소:** 전북 고창 웰파크 호텔
- **연구실:** 5개 연구실 협업
- **참가자:** 40명의 연구자
- **팀:** 10개 연구팀
- **기간:** 5박 6일
- **주제:** 뇌과학 & AI 연구

### 연구 주제
1. Emotion Contextualized Perception
2. Swift v3 개발
3. fMRI VQ-VAE Training
4. Affect-Contextualized Cognition
5. Pretrained ECoG Model
6. 4D Brain Transformer
7. 벤치마킹 스터디 디자인
8. GPU 프로그래밍 최적화
9. Genetic Transformer
10. 미정

---

## 🤝 기여하기

이것은 비공개 해커톤 웹사이트입니다. 참가자이시고 기여하고 싶으시다면:

1. 저장소 Fork
2. 기능 브랜치 생성 (`git checkout -b feature/improvement`)
3. 변경 사항 커밋 (`git commit -m 'Add some improvement'`)
4. 브랜치에 푸시 (`git push origin feature/improvement`)
5. Pull Request 열기

---

## 📞 연락처

해커톤 또는 이 웹사이트에 대한 문의:
- **GitHub:** [@yahyunee](https://github.com/yahyunee)
- **저장소:** [Hackathon_2026Winter](https://github.com/yahyunee/Hackathon_2026Winter)

---

## 📄 라이선스

이 프로젝트는 2026 Neuro-AI Grand Hackathon을 위한 것이며 교육 및 연구 목적으로 사용됩니다.

---

## 🙏 감사의 말

- [Jekyll](https://jekyllrb.com/)로 제작
- [GitHub Pages](https://pages.github.com/)에서 호스팅
- Neuro-AI 연구 커뮤니티를 위해 디자인

---

**뇌과학 연구를 가속화할 준비가 되셨나요? 해커톤에서 뵙겠습니다! 🚀**
