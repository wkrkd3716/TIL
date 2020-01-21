# 변수

> 변수는 상자를 생각하자!

### 1. 글자

- 글자는 `""`로 둘러싸인 모든것을 의미한다.

### 2. 숫자

- 정수, 실수, 복소수 복소수 등의 모든숫자를 저장할 수 있다.

### 3. 참/거짓

- 파이썬에서는 `True, False` 으로 값을 저장할 수 있다
- 주의! 각각은 대문자로 시작한다.

!!!

## github 자료 업로드 하기 !

git init 은 해당 폴더 하위만 git으로 관리하겠다!

-> 상위 ~ 폴더에서 하면 프로그램이 매우 무거워짐

git init 후에 ls -a  해보면 git이 추가된걸 확인할 수 있음



git add .   => 해당 폴더 모두를 더해줌

git status => 깃의 현 상황을 확인할 수 있음

git commit -m "python/variable 자료정리" =>  일종의 밀봉해주기

git log => commit의 기록을 보여줌

git remote add origin https://github.com/wkrkd3716/TIL.git => 깃아 원격저장소 쓸건데 추가해줘 그이름은 `오리진` , 레포짓 주소

git push origin master  => 올려줘!

cd .. 뒤로가기

cd TIL 들어가기

git diff  => 깃이 트레킹하고 있는 파일 찾고 최근에 저장된 항목을 보여줌