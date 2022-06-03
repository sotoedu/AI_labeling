파일 준비
1 최소 600 x 400 사이즈 이상
2 파일명규칙 준수  img_x.png


1 파이썬 설치
파이썬 3.8 버전 설치

2 프로그램 실행
1) 가상환경 실행

$ python -m venv venvlabel

$ source venv/bin/activate

$ git clone https://github.com/sotoedu/AI_labeling.git

$ cd AI_labeling

2) 라벨링 파일 실행
$ python run.py

3) 라벨링 작업

해당 이미지에서 labelling하고 싶은 영역을 드레그 함

1 class_list.txt 파일에는 labelling하고 싶은 키워드 입력

2 해당 이미지지에서 labelling 번호를 선택하고, 마우스로 드레그

키보드 단축키
q: quit, w: class, s: class, a: pre_img, d: next_img, e: togle

4) 분류작업
custom_dataset 폴더에 자동으로 labelling 데이터 생성됨
$ python train_test_split.py

5) 파일 압축
custom_dataset 폴더 압축 후 전달


