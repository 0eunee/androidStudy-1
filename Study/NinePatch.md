# 나인패치
## 1. 나인패치
- 이미지가 늘어나거나 줄어들 때 생기는 이미지 왜곡을 해결하는 방법
- 안드로이드에서 나인패치 이미지를 선언해줄 때는 파일 확장자 앞에 `.9` 를 붙여야 함
ex) `xxx.9.png`
- 흰색 부분 : 늘어나지 않는 영역
검은색 부분 : 늘어나는 영역

## 2. 만드는 방법
- `png`, `jpg`와 같은 이미지보다 가로, 세로 크기가 2픽셀씩 큰 이미지를 새로 만든다
- 원본 이미지를 가운데 복사
- 그 후 가장자리 한 픽셀을 흰색 or 검은색으로 수정
 
