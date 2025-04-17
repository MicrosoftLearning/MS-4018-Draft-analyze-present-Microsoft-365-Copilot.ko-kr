# Microsoft 365 Copilot과 함께 예제 데이터를 사용하여 팔로우

이 랩에서는 다음 파일을 참조하는 Microsoft 365 Copilot용 프롬프트를 만들어 보겠습니다.

- [Promotion Plan for Chai Tea in Latin America.docx](https://go.microsoft.com/fwlink/?linkid=2269126)
- [Market Analysis Report for Mystic Spice Premium Chai Tea.docx](https://go.microsoft.com/fwlink/?linkid=2268826)
- [Contoso Chai Tea 시장 추세 2023.xlsx](https://go.microsoft.com/fwlink/?linkid=2268822)

나중에 Microsoft 365 Copilot에서 이러한 파일에 액세스할 수 있도록 먼저 OneDrive에 업로드합니다.

## OneDrive에 파일 업로드

아래 단계에 따라 필요한 모든 파일을 **OneDrive**에 업로드합니다.

1. 테넌트 공급자가 제공한 가상 머신에 로컬 **관리자** 계정으로 암호를 사용하여 로그인합니다.`Pa55w.rd`

2. Windows 검색 창에 **OneDrive**를 입력하여 **OneDrive** 애플리케이션을 엽니다.

3. **이메일 주소** 프롬프트에서 userx@yourtenant.onmicrosoft.com(테넌트 공급자가 제공) 입력 후 **로그인**을 선택합니다.

4. **암호 입력** 화면에서 (테넌트 제공자가 제공한) 암호1을 입력한 다음 **로그인**을 선택합니다.

5. **이 장치의 모든 데스크톱 앱과 웹사이트에 자동으로 로그인하시겠습니까?** 라는 메시지가 표시되면 **예, 모든 앱에 해당됩니다**를 선택합니다.

6. OneDrive 폴더를 엽니다.
   
7. **파일 탐색기**의 새 인스턴스에서 **이 PC** > **로컬 디스크(C:)** 를 선택하고 **MS-4018 ResourceFiles** 폴더를 엽니다.

8. **MS-4018 ResourceFiles** 폴더 내의 모든 파일을 선택한 다음 OneDrive 폴더로 끌어서 놓습니다.

9. 업로드가 완료되면 화면 중앙 하단에 **내 파일에 3개 항목 업로드됨**이 표시됩니다.


### 참조 파일

Copilot에서 파일을 참조할 때 제공된 제안에서 일부 파일을 찾을 수 없습니다. Copilot의 특정 환경에서는 MRU(가장 최근 사용) 목록의 파일만 참조하는 반면 다른 환경에서는 OneDrive에서 파일을 직접 찾아볼 수 있기 때문에 이러한 현상이 가끔 발생합니다. 해당 목록에 추가하는 것은 적절한 Microsoft 365 앱에서 여는 것만큼 쉽습니다.  열면 MRU 목록에 표시됩니다.

> [!IMPORTANT]
> Microsoft 365 Copilot은 OneDrive에 저장된 파일에서만 작동합니다. PC에 로컬로 저장된 파일은 해당 파일을 OneDrive로 이동하여 Copilot을 활성화해야 합니다.

진행하면서 이러한 파일에 대해 다른 프롬프트를 사용해 볼 수 있으며 프롬프트 기술을 탐색하고 향상시키기 위해 그렇게 하는 것이 좋습니다.
