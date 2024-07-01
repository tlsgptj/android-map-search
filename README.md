# android-map-keyword
# 기능 구현 내용
1. 검색어 입력 및 검색 결과를 표시할 기본 레이아웃을 구현한다. 
2. 검색에 사용될 데이터를 로컬 데이터베이스에 생성한다. 
# 프로그래밍 요구 사항
1. 검색 데이터 저장은 SQLite를 사용한다. 
2. 가능한 MVVM 아키텍쳐 패턴을 적용하도록 한다.
# 구현 과정
1. database.kt파일을 생성하여 데이터베이스 생성 및 관리
2. SearchRepo에서 데이터 CRUD 작업 
3. SearchViewModel에서 데이터 처리 및 제공
4. MainActivity에서 데이터 활용
