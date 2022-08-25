# DB 연결
1. 시크릿 변수 설정
2. odmantic을 사용하여 fastapi와 연결
3. models 디렉토리를 사용하여 추상화
4. book 모델 개발
5. db에 insert

# 실행
- pip install -r requirements.txt
- python app/main.py

# 참고
- gitignore(./secrets.json)
{
    "MONGO_DB_NAME": "",
    "MONGO_URL": "",
    "NAVER_API_ID": "",
    "NAVER_API_SECRET": ""
}
