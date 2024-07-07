# KRX 주식 데이터 업데이트 프로그램

한국거래소(KRX)에 상장된 기업들의 일일 주식 가격을 가져와 MariaDB 데이터베이스에 업데이트하는 Python 기반 애플리케이션

## 기능 소개

- 네이버 금융에서 일일 최신 주식 가격을 가져옴
- 매일 지정된 시간에 주식 가격 데이터와 기업 정보를 업데이트
- 업데이트한 데이터를 MariaDB 데이터베이스에 저장
- JSON 파일을 통해 설정 가능

## requirements

- Python 3.x
- pandas
- BeautifulSoup4
- requests
- pymysql

## 설치 방법

1. repo clone:
```sh
git clone https://github.com/~
cd *Stock_Crawling*
