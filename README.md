# PythonUtilities
필요할때마다 만들어둔 파이썬 스크립트입니다.  
전부 파이썬3으로 작업했습니다.  
  
## **INI.py**
  - ini 파일을 읽어오거나 기록할 수 있습니다. 주석(;)을 구분하며 중복된 키를 허용합니다.
  - 인자가 여러개 들어가기 때문에 커맨드 가독성을 위해 argparse를 사용했습니다.
  - 기본 라이브러리 외의 의존성은 없습니다.

## **PDFToText.py**
  - 첫번째 인자로 PDF 파일의 전체경로를 넣으면 텍스트를 추출해 동일한 이름과 위치의 텍스트 파일로 저장합니다.
  - pip로 pdfminer 라이브러리를 추가하여 작업했습니다.
