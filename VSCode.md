# Visual Studio Code



### 가상환경 설정

> Python 3.5.3 (Current)
>
> Python 3.7.3 (New)

1. 시스템 환경 변수 => 환경 변수 => 사용자 변수 => Path 선택 후 편집 `~\Python37\Scripts\`,  `~\Python37\` 유무 확인

2. 시스템 환경 변수 => 환경 변수 => 시스템 변수 => Path 선택 후 편집 `C:\Program Files\Python35\Scripts\`,  `C:\Program Files\Python35\` 제거

3. Python 가상환경 생성 및 실행

   ```bash
   # 버전 확인
   $ python -V
   Python 3.7.3
   # 가상환경 폴더 생성
   $ mkdir python-virtualenv
   # 새로운 버전의 이름으로 가상환경 생성
   $ python -m venv python-virtualenv/3.7.3
   # 가상환경 실행
   $ source python-virtualenv/3.7.3/Scripts/activate
   # 정상 실행 시 아래와 같이 가상환경 이름이 표시됨
   (python-3.7.3)
   ```

4. 시스템 환경 변수 => 환경 변수 => 시스템 변수 => Path 선택 후 편집 `C:\Program Files\Python35\Scripts\`,  `C:\Program Files\Python35\` 추가

5. Python 가상환경 종료

   ```bash
   $ deactivate
   ```

   

