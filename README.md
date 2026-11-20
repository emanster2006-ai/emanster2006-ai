# Emmanuel Onwuka

Computer Science student at Liberty University, concentrating in Software Engineering. Seeking a **Summer 2027 software engineering internship**, with interests in full-stack development and AI applications.

I build projects around problems I care about, from football predictions with friends to financial document search. I also contribute to Liberty's AI Club.

## Featured work

### Rivalry Court — full-stack FPL companion

A social game where friends privately lock predictions before a Fantasy Premier League deadline, then compare results and track calibration with Brier scores.

- React and TypeScript frontend; FastAPI backend; PostgreSQL with Alembic migrations.
- Magic-link authentication, private groups, server-enforced deadlines, and append-only prediction and score records.
- API and frontend tests, PostgreSQL checks in GitHub Actions, and Docker-based local setup.
- [Try the deployed app](https://rivalry-court-web.onrender.com) (email sign-in; the free API may take about a minute to wake).
- [Public case study: screenshots, architecture, and a 60-second walkthrough](projects/rivalry-court.md).
- Code is currently private. Production end-to-end verification is still in progress.

### [SkyWatch — Liberty University AI Club](https://github.com/LU-AI-Club/ai-club-skywatch)

A school team project building aircraft detectors from ADS-B observations. **My contribution is the proximity geometry and detector integration**, not the entire platform.

- 6 merged PRs: [#9 proximity geometry](https://github.com/LU-AI-Club/ai-club-skywatch/pull/9) (local coordinate projection, velocity conversion, closest-approach time, predicted separation) and [#17 detector integration](https://github.com/LU-AI-Club/ai-club-skywatch/pull/17) (connect alignment, pair selection, geometry, and rules; one detection per aircraft pair).
- Tuning from root-cause analyses on a 1,128-detection Lynchburg replay: [#64](https://github.com/LU-AI-Club/ai-club-skywatch/pull/64) drops pairs more than 10 nm apart (1,128 to 898) and [#65](https://github.com/LU-AI-Club/ai-club-skywatch/pull/65) lowers the low-severity vertical limit from 1000 to 900 ft (1,128 to 869).
- [#88](https://github.com/LU-AI-Club/ai-club-skywatch/pull/88) analyzes where straight-line prediction breaks down near KLYH; [#96](https://github.com/LU-AI-Club/ai-club-skywatch/pull/96) adds a `detector_runs` table with start/finish heartbeats.
- A React/TypeScript proximity dashboard page is open for review ([#143](https://github.com/LU-AI-Club/ai-club-skywatch/pull/143)).
- The project scaffold, shared contracts, and the other detectors are team work.

### [SecureRAG](https://github.com/emanster2006-ai/Project-w-emanster)

A team project for financial question answering over SEC filing evidence, using hybrid retrieval, reranking, structured generation, and experimental security controls.

- **My focus:** frontend, API integration, deployment work, and CI/CD.
- **Erik's focus:** retrieval, evaluation, and ML work.
- Backend and Next.js frontend are on [`main`](https://github.com/emanster2006-ai/Project-w-emanster/tree/main/frontend).
- 44 backend unit/integration tests, frontend lint/build, and Python lint/format checks passed in the portfolio update.
- [Case study and evidence limits](projects/secure-rag.md).
- Evaluation infrastructure is implemented; comparative benchmark results have not yet been published. Live evaluation requires a separate provider-backed run.

## Tools I use

Python · TypeScript · React · Next.js · FastAPI · PostgreSQL · Docker · GitHub Actions

## Contact

- Email: [emanster2006@gmail.com](mailto:emanster2006@gmail.com)
- GitHub: [@emanster2006-ai](https://github.com/emanster2006-ai)
