# Naver Emotion Movie Corpus v1.0

네이버 영화 리뷰 감정 말뭉치입니다.

## Data description

- 각 파일은 세 개의 칼럼으로 구성되어 있습니다. `id`, `document`, `label`
    - `id`: 네이버 영화 리뷰의 아이디
    - `document`: 리뷰 내용
    - `label`: 네이버 영화 리뷰 감정 말뭉치의 감정 분류 (0: 기쁨, 1: 슬픔, 2: 두려움, 3: 분노, 4: 혐오, 5: 놀람, 6: 흥미, 7: 지루함, 8: 통증)
    - 각 열은 탭으로 구분됩니다.
    
- 전체 리뷰는 총 77,273건입니다.
    - `nemc.txt`: 전체 77,273건
    - `nemc_test.txt`: 테스트 데이터 15,457건
    - `nemc_train.txt`: 학습 데이터 61,816건
    
- 감정 어휘사전을 기반으로 구축된 감정 말뭉치 v1.0은 검수 후 업데이트될 예정입니다.

## Citation Information
- Jang, Y., Choi, J., & Kim, H. (2022, August 31). KcBert-based Movie Review Corpus Emotion Analysis Using Emotion Vocabulary Dictionary. Journal of KIISE. Korean Institute of Information Scientists and Engineers. https://doi.org/10.5626/jok.2022.49.8.608

## Contact
- yeonji3547@yonsei.ac.kr
