# This week
## Camera
### activity_importimage, activity_getimage
+  activity_importimage에서 카메라나 갤러리에서 이미지 받아와 이미지뷰에 저장후 activity_getimage로 넘기기
+ xml > external.xml 추가
+ permission ,dependency 수정 
+ 갤러리는 잘 작동 but 카메라 연동은 보완 필요

## Activity
+ toolbar 수정
## Ocr
+ 파이썬 전처리 위해 firebase에 이미지 저장 후 flask 서버로 불러와 파이썬에서 전처리 후 다시 android studio로 값 넘기기
+ 서버 주소 생성
  1) ngrok 사이트에서 zip 파일 받아 압축해제
  2)  cmd > cd 압축해제된 파일 폴더
  3) ngrok config add-authtoken 2HnBIcpGUbZ1pdR5RaTNTlBURmO_4npSCfYrDTJu1PQ83YC5w
  4) ngrok http {port 주소}
+ TestActivity.kt에서 flask 서버에서 전달받은 값을 FinancialMypageActivity.kt에 넘겨주어 table 형태로 저장

# Next week
+   **저장된 텍스트 값을 firebase db에 넘겨주어 recycler view를 구현해야함**
