# Participant Network Modernization Design

## Visual Direction

금융결제원 홍보 포스터의 밝은 흰색 여백, KFTC 블루, 깊은 네이비, 디지털 연결선 모티프를 슬라이드용 정보 디자인으로 절제해 적용한다. 각 기관 네트워크 담당자가 10m 거리의 회의실 화면에서도 회선 종단, VPN 터널 방식, QoS·NAT 처리 위치, 검증 범위를 바로 읽을 수 있도록 큰 제목, 낮은 채도의 패널, 명확한 표와 카드 중심으로 구성한다.

## Brand Reference

- Reference page: `https://www.kftc.or.kr/intro/prPoster`
- Logo asset: `assets/logo_kftc_blue.png`
- Cover network art: `assets/cover_participant_network_verified.png`
- Poster direction observed: white canvas, KFTC blue headline, deep navy hero poster, cyan/sky-blue highlight, connected dots/lines, clean public-institution tone.

## Tokens

- Page background: `#f7fbff`
- Paper white: `#ffffff`
- KFTC blue: `#0064dd`
- Deep navy: `#002b5c`
- Poster navy: `#071f46`
- Sky blue: `#19a8e5`
- Ice blue: `#eaf5ff`
- Line blue: `rgba(0, 100, 221, 0.18)`
- Primary text: `#102033`
- Secondary text: `#34506c`
- Muted text: `#6f8297`
- Warning/serial accent: `#f5a623`
- Success/ethernet accent: `#0f9d78`

## Typography

- Primary: `Noto Sans KR`, system sans-serif.
- Numeric and short technical labels: same font stack with tabular numeric settings.
- No negative letter spacing. Korean text uses `word-break: keep-all`.

## Components

- Slide surface: white/ice-blue base, top blue signal bar, subtle network grid and node motif.
- Cards: 8px radius maximum, thin blue-gray border, no nested cards.
- Tables: dense but readable, clear row separators, year chips for scanning.
- Diagrams: abstract network nodes and packet blocks only; detailed before/after 구성도는 later replacement asset.
- Cover visual: 22 협의체 기관을 실제 기관명/로고가 아닌 노드 연결망으로 형상화하고, 금융결제원 CI는 생성 이미지 내부가 아니라 실제 로고 오버레이로 표현.

## Data-Skill Rule

Every slide uses a `data-skill` value in the exact `hyperframes-slide-work-*` form, for example `hyperframes-slide-work-title` and `hyperframes-slide-work-compare`.
