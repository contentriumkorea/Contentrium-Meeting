# Third-party components

각 구성요소의 라이선스 원문은 설치 패키지의 `licenses/` 및 해당 런타임에 포함됩니다. 외부 모델은 사용자 선택과 접근 권한 확인 후 공식 배포처에서 내려받습니다.

| Component | Upstream / source | License |
| --- | --- | --- |
| .NET runtime | https://github.com/dotnet/runtime | MIT and included third-party notices |
| Microsoft WebView2 SDK | https://www.nuget.org/packages/Microsoft.Web.WebView2/1.0.4314.35 | Included SDK license and notices |
| Node.js 24.18.0 | https://nodejs.org/dist/v24.18.0/ | Included Node.js LICENSE |
| npm | https://github.com/npm/cli | Included runtime licenses |
| FFmpeg shared libraries | https://github.com/FFmpeg/FFmpeg/tree/611cec792a | LGPL 3.0 (included license) |
| FFmpeg build scripts / dependencies | https://github.com/BtbN/FFmpeg-Builds | Upstream build and dependency licenses |
| whisper.cpp (downloaded runtime) | https://github.com/ggml-org/whisper.cpp/releases/tag/b5454 | MIT |
| Whisper models (downloaded) | https://github.com/openai/whisper | MIT |
| Community-1 (downloaded) | https://huggingface.co/pyannote/speaker-diarization-community-1 | Model card terms and access conditions |
| sherpa-onnx alternative (downloaded) | https://github.com/k2-fsa/sherpa-onnx | Apache 2.0 and component notices |

FFmpeg is dynamically linked: its DLLs remain separate and replaceable. This application does not restrict modification or reverse engineering needed to debug modifications of those LGPL-covered components. FFmpeg is a trademark of Fabrice Bellard, originator of the FFmpeg project. No endorsement is implied.
