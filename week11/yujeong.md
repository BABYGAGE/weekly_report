# Camera
### activity_importimage, activity_getimage
+  activity_importimage에서 카메라나 갤러리에서 이미지 받아와 이미지뷰에 저장후 activity_getimage로 넘기기
+ xml > external.xml 추가
+ permission ,dependency 수정 
+ 갤러리는 잘 작동 but 카메라 연동은 보완 필요

# XML
+ toolbar 수정
# Ocr
+ 파이썬 전처리 위해 firebase에 이미지 저장 후 flask 서버로 불러와 파이썬에서 전처리 후 다시 android studio로 값 넘기기
