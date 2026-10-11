# 지금 이 순간 수호천사 (Guardian Angel Fortune)

일시분초에 따라 랜덤으로 수호천사가 소환되어 오늘의 운세를 알려주는 모바일 최적화 웹 서비스입니다.

## 🚀 배포 방법 (Render 사용)

이 레포지토리는 정적 파일(Static Site)로 구성되어 있어 GitHub을 통해 Render에 즉시 무료로 배포할 수 있습니다.

1. **GitHub에 업로드:**
   - 이 저장소의 내용물(`index.html` 및 `images` 폴더)을 본인의 GitHub 새 레포지토리에 Push 하거나 브라우저에서 직접 Drag & Drop 하여 업로드합니다.

2. **Render 배포 설정:**
   - [Render(render.com)](https://render.com/)에 로그인합니다.
   - 우측 상단의 **[New]** 버튼을 클릭하고 **[Static Site]**를 선택합니다.
   - 방금 만든 GitHub 레포지토리를 연결(Connect)합니다.
   - Name을 입력하고, 나머지는 기본값으로 둔 채 하단의 **[Create Static Site]**를 클릭합니다.
   - 배포가 완료되면 Render에서 제공하는 `onrender.com` URL을 통해 접속할 수 있습니다.

## 📁 디렉토리 구조 및 커스텀
- `index.html`: 메인 웹 서비스 파일입니다. (수호천사 텍스트, 애니메이션 로직 포함)
- `images/`: 실제 수호천사 이미지를 적용하려면 레포지토리 내에 `images` 폴더를 생성하고 이미지를 넣은 후, `index.html` 소스 코드 내의 `imgFallbackUrl` 경로가 올바른지 확인하시면 됩니다. (현재 코드는 `./images/캐릭터명.png`로 맵핑되어 있습니다.)