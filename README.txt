테미스 캐릭터 테스트 - Cloudflare 배포용

폴더 구조:
themis-cloudflare-ready/
├─ wrangler.jsonc
└─ public/
   ├─ index.html
   └─ images/
      └─ (아래 이미지 파일들을 넣으세요)

필요한 이미지 파일:
- cover.png
- haerok-big.png
- haerok-thumb.jpg
- ion-big.png
- ion-thumb.jpg
- kan-big.png
- kan-thumb.jpg
- kassan-big.png
- kassan-thumb.jpg
- morfeo-big.png
- morfeo-thumb.jpg
- svik-big.png
- svik-thumb.jpg
- zeon-big.png
- zeon-thumb.jpg

Cloudflare 설정:
Deploy command: npx wrangler deploy

중요:
HTML에서 images/ 경로를 사용하므로 public/images/ 안에 위 이미지 파일이 있어야
표지/결과 이미지가 정상 표시됩니다.
