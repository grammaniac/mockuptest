# GRE Verbal Mock Tests

송종옥 GRE Verbal 무료 모의고사를 제공하는 정적 웹사이트입니다(GitHub Pages).

- 대문(`index.html`)에 무료 모의고사 네 회분(`Verbal_Mock_Free_1.html` ~ `Verbal_Mock_Free_4.html`)을 싣습니다.
- 한 회분은 27문항 · 41분(Section 1 12문항 18분 + Section 2 15문항 23분)이고, 채점 뒤 문항별 해설이 열립니다.
- 회차 파일은 검색엔진 색인을 막아 두었고(noindex), 대문만 색인됩니다.
- 2026-11-12: 옛 38회·39회(해설 없음)를 삭제하고 네 회분으로 교체했습니다. 그 이전 회차(17~37회) HTML 20개도 같은 날 삭제했습니다(해설 없는 옛 자료).

GRE Verbal 정보와 수업 안내는 [greverbal.com](https://greverbal.com/)에 있습니다. 문의는 [카카오톡 오픈채팅](https://open.kakao.com/o/s0ifxj1f)으로 받습니다.

## 회차 파일 만드는 곳

회차 HTML은 이 저장소에서 직접 고치지 않습니다. 생성기(`GRE_MockTest_Project_Frequencies/생성기_v2/select_pub.py` → `build_pub.py`)가 만든 파일을 복사해 넣습니다.

## 로컬 미리보기

```sh
python3 -m http.server 8000
```
