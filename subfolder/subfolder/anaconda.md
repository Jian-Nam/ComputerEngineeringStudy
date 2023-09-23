#ComputerEngineering #Language #Python

가상 환경 생성
```
conda create -n 가상환경이름 
conda create -n 가상환경이름 python=2 
conda create -n 가상환경이름 python=3.7
```

가상 환경 확인
```
conda env list 
conda info envs
```

가상 환경 활성화
```
conda activate 가상환경이름
```

가상 환경 비활성화
```
conda env remove -n 가상환경이름
```

패키지 설치
```
conda install 라이브러리이름
```

패키지 확인
```
conda list
```

패키지 삭제
```
conda remove 라이브러리이름 
conda remove -n 가상환경이름 라이브러리이름
```

패키지 리스트 저장
```
conda list --export > packagelist.txt
```

패키지 리스트 설치
```
conda install --file packagelist.txt
```