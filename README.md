# Learn GitHub - GitHub 학습 프로젝트

## 프로젝트 개요
이 프로젝트는 **GitHub 사용법을 학습하기 위한 연습용 저장소**입니다.
각 사용자는 자신의 폴더를 만들고, `introduce.md` 파일을 작성하여 자기소개를 추가할 수 있습니다.

## 주요 학습 내용
- Git 저장소 초기화 및 클론 (`git init`, `git clone`)
- 브랜치 생성 및 관리 (`git branch`, `git checkout`)
- 변경 사항 커밋 (`git add`, `git commit`)
- 원격 저장소에 푸시 (`git push`)
- Pull Request(PR) 생성 및 병합
- GitHub Flow 실습

## 프로젝트 구조
```
learnGithub/
│── baek/introduce.md  # baek의 자기소개 파일
│── boram/introduce.md  # boram의 자기소개 파일
│── geoff/introduce.md  # geoff의 자기소개 파일
│── hyeondo/introduce.md  # hyeondo의 자기소개 파일
│── jaehong/introduce.md  # jaehong의 자기소개 파일
│── jimin/introduce.md  # jimin의 자기소개 파일
│── wooyong/introduce.md  # wooyong의 자기소개 파일
│── LICENSE  # 프로젝트 라이선스
│── README.md  # 프로젝트 설명 파일
```

## Git 사용 방법
### 1. 저장소 클론
```bash
git clone <repository-url>
cd learnGithub
```

### 2. 새 브랜치 생성 및 이동
```bash
git checkout -b feature/yourname
```

### 3. 자기소개 파일 작성
```bash
echo "# 자기소개" > yourname/introduce.md
git add yourname/introduce.md
git commit -m "Add introduce file for yourname"
```

### 4. 변경 사항 원격 저장소로 푸시
```bash
git push origin feature/yourname
```

### 5. Pull Request(PR) 생성
1. GitHub에서 PR 생성
2. 코드 리뷰 및 피드백 반영
3. PR 병합 후 브랜치 삭제

## 기여 방법
1. 본 레포지토리를 포크합니다.
2. 새로운 브랜치를 생성합니다.
3. 변경 사항을 커밋하고 푸시합니다.
4. Pull Request를 생성하여 기여합니다.

## 라이선스
이 프로젝트는 MIT 라이선스를 따릅니다.

