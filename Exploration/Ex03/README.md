# AIFFEL Campus Online Code Peer Review Templete
- 코더 : 하강혁
- 리뷰어 : 황동주


# PRT(Peer Review Template)
- [O]  **1. 주어진 문제를 해결하는 완성된 코드가 제출되었나요?**
    - 문제에서 요구하는 최종 결과물이 첨부되었는지 확인
        - 중요! 해당 조건을 만족하는 부분을 캡쳐해 근거로 첨부
        - ![image](https://github.com/user-attachments/assets/0ba26a0d-2a72-411f-8891-66f044210a24)
        - ![image](https://github.com/user-attachments/assets/b6541963-3cc3-4887-b24d-4a2862df374c)
        - 이미지 로드 에서 부터 얼굴 검출 및 랜드스케이프 검출까지 잘 되었습니다.
        - 고양이 수염 합성이 잘 되었습니다.


    
- [X]  **2. 전체 코드에서 가장 핵심적이거나 가장 복잡하고 이해하기 어려운 부분에 작성된 
주석 또는 doc string을 보고 해당 코드가 잘 이해되었나요?**
    - 해당 코드 블럭을 왜 핵심적이라고 생각하는지 확인
    - 해당 코드 블럭에 doc string/annotation이 달려 있는지 확인
    - 해당 코드의 기능, 존재 이유, 작동 원리 등을 기술했는지 확인
    - 주석을 보고 코드 이해가 잘 되었는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - 주석 부분이 미흡 했던게 아쉬운 부분 같습니다.
        
- [O]  **3. 에러가 난 부분을 디버깅하여 문제를 해결한 기록을 남겼거나
새로운 시도 또는 추가 실험을 수행해봤나요?**
    - 문제 원인 및 해결 과정을 잘 기록하였는지 확인
    - 프로젝트 평가 기준에 더해 추가적으로 수행한 나만의 시도, 
    실험이 기록되어 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - ![image](https://github.com/user-attachments/assets/44bd17aa-d0fd-404b-bd10-83dcb07b3911)
        - 얼굴 사진이 살짝 기울어져 있어서 고양이 수염 사진을 getRotationMatrix2D 으로 회전을 시도 하신게 좋았습니다.
        - ![image](https://github.com/user-attachments/assets/ccbc6273-a47d-4e90-a544-4ab0512dd053)
        - addWeighted 를 사용하여 합성을 시도 해본 점이 좋았습니다.

        
- [X]  **4. 회고를 잘 작성했나요?**
    - 주어진 문제를 해결하는 완성된 코드 내지 프로젝트 결과물에 대해
    배운점과 아쉬운점, 느낀점 등이 기록되어 있는지 확인
    - 전체 코드 실행 플로우를 그래프로 그려서 이해를 돕고 있는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - 회고 부분이 미흡 했던게 아쉬운 부분 같습니다.
        
- [O]  **5. 코드가 간결하고 효율적인가요?**
    - 파이썬 스타일 가이드 (PEP8) 를 준수하였는지 확인
    - 코드 중복을 최소화하고 범용적으로 사용할 수 있도록 함수화/모듈화했는지 확인
        - 중요! 잘 작성되었다고 생각되는 부분을 캡쳐해 근거로 첨부
        - ![image](https://github.com/user-attachments/assets/0393db9d-1be9-4995-bde6-4f70cad302a1)
        - 얼굴 및 랜드마크 검색 부터 합성까지 코드 잘 작성 하셨습니다.



# 회고(참고 링크 및 코드 개선)
```
# 리뷰어의 회고를 작성합니다.
# 코드 리뷰 시 참고한 링크가 있다면 링크와 간략한 설명을 첨부합니다.
# 코드 리뷰를 통해 개선한 코드가 있다면 코드와 간략한 설명을 첨부합니다.
```
- 기본적인 이미지 로드 에서 부터 얼굴 검출 및 랜드스케이프 검출까지 잘 되었습니다.
- 설정하신 사진이 약간 회전 되어 있어 합성하기 어려웠을 거 같습니다.
- 여러 이미지 사진을 좀 더 시도 해 보았으면 좋았을 거 같은 아쉬움이 있습니다.
- 고양이 수염 사진을 getRotationMatrix2D 로 회전 시켜 합성하려는 시도가 좋았습니다.
- 수고 많이 하셨습니다.