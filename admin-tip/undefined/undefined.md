# 윈도우 방화벽 설정

이 자습서에서는 윈도우에서 윈도우 방화벽에서 Votifier 포트인 8192 포트를 허용하는 방법에 대해 서술해요. 마인크래프트 Java 서버인 경우 8192 포트가 아닌 25565 포트를 사용해 주세요.

1. 제어판을 통해 윈도우 Defender 방화벽에 들어갑니다. (직접 제어판에서 들어가거나, 윈도우 키를 누른 후 방화벽을 검색하여 들어갈 수 있습니다)
2.  초록색으로 체크 표시가 된 모습을 확인할 수 있습니다. 초록색 체크 표시가 되어 있어야 방화벽이 정상적으로 작동하고 있는 상태입니다. 빨간색은 경우 외부로부터의 해킹에 취약할 수 있으니 권장하지 않습니다. 좌측에 고급 설정 버튼을 눌러줍니다.

    ![https://s3.amazonaws.com/helpscout.net/docs/assets/5a26cd182c7d3a1a640c9a5d/images/5a65e4240428632faf620694/file-NERpdjyHPS.png](https://s3.amazonaws.com/helpscout.net/docs/assets/5a26cd182c7d3a1a640c9a5d/images/5a65e4240428632faf620694/file-NERpdjyHPS.png)
3. 사용자 계정 컨트롤 창이 뜬다면 예 버튼을 눌러줍니다.
4.  좌측 인바운드 규칙을 누른 후 우측에 새 규칙 버튼을 눌러줍니다.

    ![https://s3.amazonaws.com/helpscout.net/docs/assets/5a26cd182c7d3a1a640c9a5d/images/5a65e4402c7d3a39e626380b/file-DCttiiL8aq.png](https://s3.amazonaws.com/helpscout.net/docs/assets/5a26cd182c7d3a1a640c9a5d/images/5a65e4402c7d3a39e626380b/file-DCttiiL8aq.png)
5.  포트를 선택하고 다음 버튼을 눌러줍니다.

    ![https://s3.amazonaws.com/helpscout.net/docs/assets/5a26cd182c7d3a1a640c9a5d/images/5a65e4470428632faf620696/file-jWIGMaThZV.png](https://s3.amazonaws.com/helpscout.net/docs/assets/5a26cd182c7d3a1a640c9a5d/images/5a65e4470428632faf620696/file-jWIGMaThZV.png)
6.  TCP를 선택하고 8192를 입력후 다음 버튼을 눌러줍니다.

    ![https://s3.amazonaws.com/helpscout.net/docs/assets/5a26cd182c7d3a1a640c9a5d/images/5a65e44b2c7d3a39e626380d/file-BjKmaWyY6M.png](https://s3.amazonaws.com/helpscout.net/docs/assets/5a26cd182c7d3a1a640c9a5d/images/5a65e44b2c7d3a39e626380d/file-BjKmaWyY6M.png)
7.  연결 허용을 선택하고 다음 버튼을 눌러줍니다.

    ![https://s3.amazonaws.com/helpscout.net/docs/assets/5a26cd182c7d3a1a640c9a5d/images/5a65e4652c7d3a39e6263811/file-nKteLqP8ae.png](https://s3.amazonaws.com/helpscout.net/docs/assets/5a26cd182c7d3a1a640c9a5d/images/5a65e4652c7d3a39e6263811/file-nKteLqP8ae.png)
8.  모두 체크하고 다음 버튼을 눌러줍니다.

    ![https://s3.amazonaws.com/helpscout.net/docs/assets/5a26cd182c7d3a1a640c9a5d/images/5a65e4502c7d3a39e626380e/file-jxSh4PVTVo.png](https://s3.amazonaws.com/helpscout.net/docs/assets/5a26cd182c7d3a1a640c9a5d/images/5a65e4502c7d3a39e626380e/file-jxSh4PVTVo.png)
9.  Votifier 규칙의 이름을 입력하고 다음 버튼을 눌러줍니다. 이름은 아무 것이나 입력해도 무방합니다.

    ![https://s3.amazonaws.com/helpscout.net/docs/assets/5a26cd182c7d3a1a640c9a5d/images/5a65e4550428632faf620697/file-b3wUJgNH82.png](https://s3.amazonaws.com/helpscout.net/docs/assets/5a26cd182c7d3a1a640c9a5d/images/5a65e4550428632faf620697/file-b3wUJgNH82.png)
