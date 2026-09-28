# comfyui-assets

ComfyUI(server238, Wan 2.2 I2V 등)에 넣을 **입력 이미지** 공개 저장소입니다. **공개 repo이므로 민감한 이미지는 올리지 마세요.**

## 올리기
- Mac: `comfy-asset <이미지>` → raw URL 출력(클립보드 복사) + server238 즉시 동기화
- 웹/휴대폰: 이 repo에서 `Add file → Upload files` (server238이 30초 안에 자동 동기화)

## MCP(ChatGPT/Claude)에서 쓰기
server238이 이 repo를 ComfyUI `input/comfyui-assets/`에 30초마다 동기화합니다. raw URL을 워크플로 `LoadImage`의 `image` 값으로 바꾸는 규칙:

```
https://raw.githubusercontent.com/aiinplanet/comfyui-assets/main/<경로>
→ LoadImage image = comfyui-assets/<경로>
```

예) `https://raw.githubusercontent.com/aiinplanet/comfyui-assets/main/2026/09/20260928-170000-abc123-cat.png`
→ `comfyui-assets/2026/09/20260928-170000-abc123-cat.png`
