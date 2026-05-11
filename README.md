# 든든피플 예약 신청 폼

든든피플(dendenpeople.com) 인력매칭 예약 신청용 정적 폼 페이지.

- GitHub Pages 배포: https://jehyeong2.github.io/denden-booking-form/
- 폼 제출 → cloudflared tunnel을 통해 n8n booking webhook으로 전송
- Daum 우편번호 / 캘린더 / 시작·종료 시간 드롭다운 지원

## URL 파라미터

- `?k=<kakao_user_key>`: 카카오톡에서 진입 시 사용자 식별자
- `?api=<webhook_url>`: 폼 제출 webhook URL override (운영 도메인 변경 시)
