# Vulnerzone_Detector
3D 모델의 출력시 충격에 취약한 부분을 모델링 단계부터 인지하기 위해 제작하였음.
코드 작성은 ChatGPT의 도움을 받음.

[사용법]
1. 취약한 부분을 확인하고자 하는 3D 모델을 Fusion 360 또는 AUTOCAD등을 이용하여 2D 도면(이하 PNG파일)을 제작
2. 사용자의 구글 드라이브에 PNG파일 이름을 TestImage.png로 변경하여 업로드, Vulnerzone Detector Model.h5 모델 파일 업로드
3. threshold 값을 0.5~1까지 적절히 조정하여 코드를 실행
4. 출력된 결과(marked_image.png)를 확인하여 취약한 부분 식별
5. 취약한 부분이 있음에도 불구하고 No vulnerability detected 가 출력되면 threshold 값을 높여서 재시도
