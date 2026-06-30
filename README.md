# 🍳 냉장고 털기 요리사

있는 재료로 AI가 딱 맞는 요리를 추천해주는 웹앱입니다.

## 🚀 CodeSandbox로 배포하기 (무료, 5분)

### 1단계 - CodeSandbox 업로드
1. [codesandbox.io](https://codesandbox.io) 접속 → 로그인
2. **"+ Create"** 클릭 → **"Import from ZIP"** 선택
3. 이 zip 파일을 업로드

### 2단계 - 공개 URL 받기
- 자동으로 `https://xxxxxx.csb.app` 형식의 URL이 생성됩니다
- 우측 상단 **Share** → **"Public"** 으로 설정하면 누구나 접속 가능!

---

## ☁️ Vercel로 배포하기 (더 빠른 URL, 무료)

```bash
npm install -g vercel
cd recipe-app
npm install
vercel --prod
```
→ `https://recipe-finder-xxx.vercel.app` 형태의 URL 생성

---

## 기능
- 🥦 보유 재료 태그 입력
- 🧂 기본 양념 입력
- ⏱ 조리 시간 / 난이도 선택
- ✨ AI 요리 추천 카드 (일치도 순 정렬)
- 📊 재료 일치도 게이지
- 👨‍🍳 단계별 조리법
- ⚠️ 부족한 재료 & 대체 재료
- 🛒 최소 장보기 목록
