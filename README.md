# 목포 먹방 1박 2일

정적 사이트(HTML 1개 + 지도 이미지 4개)라서 빌드 없이 바로 호스팅할 수 있어요.

- `index.html`: 페이지 전체 (일정, 41곳 목록, 지도)
- `map-main.jpg`, `map-hadang.jpg`: 카카오맵 캡처를 이어 붙인 지도
- `map-main-mask.png`, `map-hadang-mask.png`: 지도 가장자리를 부드럽게 처리하는 마스크

로컬 확인: `npx serve .` 후 브라우저에서 열기
(파일을 더블클릭해서 열면 지도 이미지가 안 뜰 수 있어요)
