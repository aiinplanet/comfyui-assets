# comfyui-assets

ComfyUI(server238, Wan 2.2 I2V 등)에 넣을 **입력 이미지**를 URL로 만들기 위한 공개 저장소입니다. **공개 repo이므로 민감한 이미지는 올리지 마세요.**

## 올리기
- Mac: `comfy-asset <이미지>` → raw URL 출력(클립보드 복사)
- 웹/휴대폰: 이 repo에서 `Add file → Upload files` 후 파일의 **Raw** 주소 사용

## MCP(ChatGPT/Claude)에서 쓰기
raw URL을 MCP에 주면 `upload_image_from_url` 도구가 이미지를 받아 ComfyUI `input/mcp-in/`에 올리고,
워크플로 `LoadImage`의 `image`에 넣을 값(`mcp-in/...`)을 돌려줍니다. 서버가 이 repo를 자동으로 가져가지는 않습니다.

예) ChatGPT에 "이 이미지로 I2V 해줘: https://raw.githubusercontent.com/aiinplanet/comfyui-assets/main/2026/09/xxxx.png"
