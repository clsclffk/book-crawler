# 📚 교보문고 IT 스테디셀러 크롤링 실습
- 교보문고의 컴퓨터/IT 분야 스테디셀러 50권의 정보를 크롤링하여 CSV 파일 및 MySQL 데이터베이스에 저장
- Selenium과 BeautifulSoup을 이용해 실시간 웹페이지에서 IT 도서 정보를 수집
- 수집 데이터를 판다스로 정리해 `.csv` 및 MySQL로 저장

## 🔍 크롤링 대상

- **웹페이지**: [교보문고 IT 스테디셀러](https://store.kyobobook.co.kr/bestseller/steady/domestic/33?page=1&per=50)
- **기간**: 2024.11.11 ~ 2024.11.17
- **수집 항목**:  
  - 책 제목  
  - 저자  
  - 출판사  
  - 가격  
  - 출판일  
  - 별점  
  - 리뷰 수  
  - 할인율  

## 🛠 사용 기술
- `BeautifulSoup`, `Selenium` → 웹 페이지 크롤링
- `re`, `pandas` → 텍스트 정제 및 DataFrame 변환

## 📁 주요 파일

| 파일명 | 설명 |
|--------|------|
| `13_교보문고.ipynb` | 크롤링 및 저장 전체 코드 |
| `it_books.csv` | 크롤링한 데이터를 저장한 CSV |
| `my_sql_result2.png` | MySQL에 저장된 결과 스크린샷 |

