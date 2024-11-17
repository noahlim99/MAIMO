<MAIMO_Prototype>
  
1. 이미지 입력하는 UI (No Coding tool)
2. 입력받은 이미지 google drive/AIDS Project/Images에 저장
3. 코드 실행 : 
   저장된 이미지의 텍스트를 pytesseract 모델 사용하여 추출
   추출된 text 파일은 google drive/AIDS Project/texts에 저장
   Solar pro API 접속
     과목 분류(입력받은 과목 중 해당하는 과목)
     요약
     필요한 추가 정보 제공
4. 해당 내용을 띄우는 UI (No Coding tool)
5. "새로운 이미지 입력" 버튼 (이 때 드라이브의 기존 이미지와 텍스트 파일 삭제, Solar 초기화 됨)
