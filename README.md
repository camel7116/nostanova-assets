# nostanova-assets
nostanova.com 홈페이지 히어로 영상(무음, H.264). jsDelivr CDN 으로 제공.
- hero_1080.mp4 1920×1080 · hero_720.mp4 1280×720

## 운영 메모 (스밈)
- 원본: 노스타노바_홈페이지_pre2.mp4 (1920×1080 42MB) → ffmpeg crf26(1080)/27(720), 무음, faststart.
- 사이트는 태그로 고정해 쓴다: `https://cdn.jsdelivr.net/gh/camel7116/nostanova-assets@v1/hero_1080.mp4`
- 영상을 바꾸면 파일 교체 → 커밋 → 새 태그(v2) → 사이트 URL 의 @v1 을 @v2 로 (jsDelivr 는 태그별로 영구 캐시).
- jsDelivr 한도: 파일당 20MB, 무료.
