## Sourcekit-LSP란?
Swift와 C-based 언어를 위한 Language Server Protocol입니다. 각종 에디터 상에서 볼 수 있는 code-completion, jump-to-definition 같은 기능들을 제공합니다. 

### 사용법
SourecKit-LSP는 Swift toolchain에 포함되어 있으므로 상황에 따라 이미 사용이 가능한 상태일 수도 있습니다. 호환성을 보장하기 위해 사용하고자 하는 sourcekit-lsp에 맞는 toolchain 버전을 사용하시기 바랍니다. 모든 명령어는 터미널에서 작업하시면 됩니다.
1. Get SourceKit-LSP
	 - Xcode 버전이 11.4+라면,  `xcrun sourcekit-lsp` 명령어로 실행시킬 수 있습니다.
	 - [이 곳](https://swift.org/download/)에 있는 toolchain을  사용하는 경우라면, 맥에서는 `xcrun --toolchain swift sourcekit-lsp` 명령어로 실행이 가능하고 리눅스에서는 sourcekit-lsp가 있는 전체 경로를 사용하라고 하는데 리눅스에서는 해본 적이 없으므로 직접 확인해보시고 알려주시기 바랍니다!
	 - sourcekit-lsp가 없는 toolchain을 사용하고 있다면, [이 곳](https://swift.org/download/)에서 자신의 환경에 맞는 최신 toolchain을 설치하시고 윗 항목처럼 진행하시기 바랍니다.
