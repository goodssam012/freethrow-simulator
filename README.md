# 🏀 자유투 연습 시뮬레이터

웹캠으로 두 손과 팔 자세를 인식해 자유투를 연습하는 브라우저 시뮬레이터입니다.

- MediaPipe Hand/Pose Landmarker로 두 손과 팔꿈치 각도 인식
- 시작할 때 큰 화면에서 자세 보정 (손 위치·팔 각도 가이드)
- 두 손으로 공을 잡고 위로 밀어 올리면 슛
- Three.js 3D 코트, 림·백보드 물리

## 실행
웹캠 권한이 필요하며 HTTPS 또는 localhost에서 동작합니다.

```bash
python -m http.server 8123
```

브라우저에서 http://localhost:8123 접속.

## 키보드
Space: 슛 게이지 · 방향키: 조준/각도 · V: 리플레이 · K: 재보정
