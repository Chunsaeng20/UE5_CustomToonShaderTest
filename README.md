# UE5_CustomToonShaderTest

본 레포지토리는 언리얼 엔진 5 소스코드를 사용하여 커스텀 툰 셰이더를 제작하는 것을 목표로 한다.

## Getting up and running

1. 언리얼 엔진 5 소스코드를 [다운로드](https://github.com/EpicGames/UnrealEngine)한다.

    - 에픽게임즈 계정과 GitHub 계정이 필요하다.
    - [UnrealEngine.com](https://www.unrealengine.com/ko)에 로그인하여 '계정'에서 GitHub 계정과 연동한다.
    - GitHub에 등록된 이메일로 전송된 @EpicGames 초대 이메일을 수락한다.
    - 언리얼 엔진 5 레포지토리를 clone하거나 zip파일을 다운로드한다.
    - 레포지토리를 clone하고 싶다면 fork한 후 clone하는 것을 권장한다.
    - 자세한 내용은 [이곳](https://www.unrealengine.com/ko/ue-on-github)을 참조한다.

2. 레포지토리의 파일을 소스코드가 들어있는 폴더에 붙여넣기한다.

3. 언리얼 엔진 5를 빌드한다.

    - Setup.bat을 실행한다.
    - GenerateProjectFiles.bat을 실행한다.
    - UE4.sln을 Visual Studio로 로드하여 UE4를 타깃으로 Build한다.
    - 자세한 내용은 [이곳](https://docs.unrealengine.com/5.3/ko/downloading-unreal-engine-source-code/)을 참조한다.

4. [언리얼 디퍼드 렌더를 이용한 툰 렌더링 제작기](https://epiclounge.co.kr/contents/replay_view.php?idx=1270)를 참고하여 커스텀 셰이더를 제작한다.

## Troubleshooting

- 빌드 에러가 난 경우 언리얼 엔진 5 소스코드가 들어있는 폴더를 확인한다. 만약 폴더의 경로가 길거나 폴더의 이름이 길 경우 오류가 날 수 있다.

- C:\나 C:\Program Files\에 언리얼 엔진 5 소스코드 폴더를 두는 것을 권장한다.

- 언리얼 엔진 5 소스코드를 빌드할 경우 200GB 정도의 여유 공간을 두는 것을 권장한다.

- 언리얼 엔진 5 소스코드는 매우 무겁기 때문에 언리얼 엔진 5 소스코드의 수정은 개발이 어느 정도 진행된 이후에 그 결과를 확인하기 위하여 사용하는 것을 권장한다.

## Unreal Engine License

언리얼 엔진의 라이센스는 End User License Agreement (EULA)가 적용된다. 관련된 사항은 [언리얼 엔진 다운로드 페이지](https://www.unrealengine.com/ko/download)에서 확인할 수 있다. EULA의 이용약관에 동의하지 않으면 언리얼 엔진을 사용할 수 없다.

## License

본 레포지토리는 누구나 자유롭게 사용가능하다.

## Contributions

Pull request는 받지 않는다.

## Additional Notes

본 레포지토리는 언리얼 엔진 5.3.1을 기반으로 만들어졌다.

추가적인 정보를 얻고싶다면 다음을 둘러볼 것을 권장한다.

- [official documentation](https://docs.unrealengine.com)
- [Programming and Scripting in Unreal Engine](https://docs.unrealengine.com/unreal-engine-programming-and-scripting)
- [Development Setup](https://docs.unrealengine.com/setting-up-your-development-environment-for-cplusplus-in-unreal-engine/)
- [Working with the GitHub source code distribution](https://docs.unrealengine.com/downloading-unreal-engine-source-code)
- [Unreal Engine C++ API Reference](https://docs.unrealengine.com/API)
- [Discussion](https://forums.unrealengine.com/latest?exclude_tag=question)
- [Q&A](https://forums.unrealengine.com/tag/question)
- [Epic Games Dev Community](https://dev.epicgames.com/community/)