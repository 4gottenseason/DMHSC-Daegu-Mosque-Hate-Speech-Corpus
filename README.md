# DMHSC: Daegu Mosque Hate Speech Corpus
대구 이슬람 사원 건축 논란과 관련된 혐오 담화를 수집·정제한 한국어 말뭉치입니다. 말뭉치언어학, 비판적 담화분석, 혐오 발화 탐지 연구를 위해 설계되었습니다.

## 📌 소개 (Introduction)
이 레포지토리는 **대구 이슬람 사원 건축 논란**과 관련된 혐오 담화 자료를 수집·정제하여 구축한 한국어 말뭉치입니다.  
온라인(뉴스 기사, 댓글, SNS) 및 오프라인(현수막, 집회 발언 등)에서 나타난 **반(反)무슬림 담론**을 포함합니다.

본 데이터셋은 다음 연구 분야에 활용할 수 있습니다:
- 말뭉치언어학 (Corpus Linguistics)
- 비판적 담화분석 (Critical Discourse Analysis)
- 혐오 발화 탐지 (Hate Speech Detection)
- 사회언어학 및 사회적 편견 연구

---

## 📂 데이터 구성 (Dataset Composition)
- **형식**: CSV
- **언어**: 한국어
- **크기**: 약 26MB, 30,981개 댓글, 489,959 어절
- **주요 필드**
  1) 출처 (Source): 해당 댓글이 업로드된 유튜브 영상의 URL
  2) 작성자 (Author ID): 댓글 작성자의 YouTube 사용자 ID
  3) 좋아요 수 (Likes): 댓글의 좋아요 수 (2025년 3월 기준)
  4) 작성 시간 (Timestamp): 댓글 작성 일자
  5) 댓글 (Comment): 원문 댓글 텍스트 데이터
  6) 댓글_POS (Comment_POS): 댓글에 대한 형태소 분석 결과(KIWI 형태소 분석기 사용)
  7) 의미단위_병합 (Merged Semantic Units): 자주 출현한 2-gram 단위를 기반으로, 다단어 어휘 표현을 하나의 단위로 병합한 결과

---

## ⚖️ 연구 윤리 및 사용 주의 (Ethical Considerations)
본 데이터셋은 **혐오 표현을 포함**하고 있으며, 학술·연구 목적으로만 사용해야 합니다.  
모델 학습, 분석, 재배포 시 다음 사항을 준수해야 합니다:
- 개인정보 포함 시 익명화 처리 필수
- 데이터의 상업적 이용 금지
- 연구 결과 발표 시 본 레포지토리 인용
- 차별, 폭력, 혐오 조장 목적 사용 금지

---

## 📜 라이선스 (License)
본 프로젝트는 [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/) 라이선스를 따릅니다.  
즉, **비영리 목적**에서 자유롭게 활용할 수 있으며, 출처 표기가 필요합니다.

---

📬 문의 (Contact)
- Author: 이준
- Email: leejun0624@yonsei.ac.kr

