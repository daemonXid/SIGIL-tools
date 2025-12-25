# 🛠️ SIGIL-TOOLS

> **Privacy-First Web Tools for Students**  
> 대학생을 위한 프라이버시 우선 웹 도구 모음

[![GitHub Pages](https://img.shields.io/badge/demo-live-success)](https://daemonxid.github.io/SIGIL-TOOLS/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![DAEMON Architecture](https://img.shields.io/badge/DAEMON-Architecture-purple)](https://github.com/daemonxid)

## ✨ Features

모든 도구는 **브라우저 내에서 처리**되며, 데이터는 서버로 전송되지 않습니다.

### 📚 Academic Tools

- **🎯 GPA Calculator** - 학점 계산기 (4.5/4.3 지원)
- **📝 Resume Builder** - Markdown → PDF 이력서 빌더
- **📖 Citation Generator** - APA/MLA/Chicago 인용구 생성

### ⏰ Productivity Tools

- **🍅 Pomodoro Timer** - 할 일 목록 통합 집중 타이머
- **🎲 Meeting Roulette** - 팀 발표자/서기 선정 룰렛
- **📅 Project Roadmap** - Mermaid Gantt 차트 시각화

### 💰 Lifestyle Tools

- **💸 Expense Splitter** - 더치페이 계산기 (카톡 공유 기능)

### 🎨 Design & Media Tools

- **🖼️ Image Batch Resizer** - 이미지 일괄 압축/리사이즈
- **🔒 Privacy Blur Tool** - 사진 개인정보 블러 처리
- **🎨 Color Palette Extractor** - 이미지 색상 추출

## 🏗️ Tech Stack (The Zen Stack)

```
Frontend:  HTML5 + Tailwind CSS + Alpine.js
Effects:   Canvas API (Liquid Background)
Storage:   LocalStorage / IndexedDB
Libraries: jsPDF, Mermaid.js, JSZip
Deploy:    GitHub Pages
```

## 🚀 Quick Start

### Local Development

```bash
# Clone repository
git clone https://github.com/daemonxid/SIGIL-TOOLS.git
cd SIGIL-TOOLS

# Serve locally
python3 -m http.server 8000

# Open browser
open http://localhost:8000
```

### Deploy to GitHub Pages

Already configured! Just push to `main` branch and GitHub Actions will deploy automatically.

## 📂 Project Structure

```
SIGIL-TOOLS/
├── index.html                    # Main landing page
├── sigil-liquid-effect.html      # Liquid effect component (SIGIL)
├── tools/                        # All tool implementations
│   ├── gpa-calculator.html       # ✅ GPA Calculator
│   ├── pomodoro-timer.html       # ✅ Pomodoro Timer
│   ├── expense-splitter.html     # ✅ Expense Splitter
│   ├── citation-generator.html   # ✅ Citation Generator
│   └── meeting-roulette.html     # ✅ Meeting Roulette
├── .github/
│   └── workflows/
│       └── deploy.yml            # GitHub Pages deployment
├── LICENSE
└── README.md
```

## 🎨 Design Philosophy

이 프로젝트는 **DAEMON Architecture**와 **Component Driven Development (CDD)** 원칙을 따릅니다:

1. **Simple > Complex**: 단일 HTML 파일로 각 도구 구현
2. **Privacy-First**: 모든 처리는 브라우저 내에서 완료
3. **Vertical Slicing**: 각 도구는 독립적인 수직 슬라이스
4. **Modern Stack**: Canvas API, Web APIs, ES6+ 활용
5. **CDD**: SIGIL 컴포넌트 검증 후 통합

## 🔒 Privacy Commitment

- ✅ No server-side processing
- ✅ No data collection
- ✅ No external API calls (except CDNs)
- ✅ 100% client-side computation
- ✅ Open source & auditable

## 🛣️ Roadmap

- [x] Liquid Effect Background
- [x] Landing Page with Category Filter
- [x] GPA Calculator ✅ **LIVE**
- [x] Pomodoro Timer ✅ **LIVE**
- [x] Expense Splitter ✅ **LIVE**
- [x] Citation Generator ✅ **LIVE**
- [x] Meeting Roulette ✅ **LIVE**
- [ ] Resume Builder (jsPDF integration)
- [ ] Project Roadmap (Mermaid.js)
- [ ] Image Batch Resizer (Canvas API)
- [ ] Privacy Blur Tool
- [ ] Color Palette Extractor

## 📜 License

MIT License - feel free to use for your own projects!

## 🙏 Acknowledgments

Built with ❤️ using:

- [Tailwind CSS](https://tailwindcss.com/)
- [Alpine.js](https://alpinejs.dev/)
- [jsPDF](https://github.com/parallax/jsPDF)
- [Mermaid.js](https://mermaid.js.org/)

---

**Made with 😈 DAEMON Architecture** | [GitHub](https://github.com/daemonxid)
