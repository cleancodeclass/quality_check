# quality_check
코드 품질 체크 Session


# SonarQube
- Server 다운로드 (https://binaries.sonarsource.com/Distribution/sonarqube/sonarqube-7.4.zip)
- Client 다운로드 (https://binaries.sonarsource.com/Distribution/sonar-scanner-cli/sonar-scanner-cli-4.0.0.1744-windows.zip)
  
- Server 설치
1. 다운로드한 파일 압축풀기
2. 서버실행
	- StartSonar.bat 실행 (sonarqube-7.4\bin\windows-x86-64\StartSonar.bat)
	- 서버실행 확인 (http://localhost:9000)
	![image](https://user-images.githubusercontent.com/42139382/66746721-863ec100-eebd-11e9-9168-850c81d12d01.png)
	
	
3. 

- Client 설치
1. 다운로드한 파일 압축풀기
2. 환경변수 설정
3. 윈도우 cmd 에서 sonar-scanner 명령어 확인
![image](https://user-images.githubusercontent.com/42139382/66745823-09aae300-eebb-11e9-8b1b-5459567feefa.png)

- sonar-project.properties 파일 적용
1. 파일 만들기
```
sonar.projectKey=ccc:gildedrose
sonar.projectName=GildedRose
sonar.projectVersion=1.0

sonar.sourceEncoding=UTF-8

sonar.sources=src/main/java
sonar.java.binaries=bin

sonar.host.url=http://localhost:9000

sonar.login=admin
sonar.password=admin
```
2. 파일 배치
인스펙션할 프로젝트 Root에 파일 배치
![image](https://user-images.githubusercontent.com/42139382/66747193-e84bf600-eebe-11e9-825e-5b6823985c9c.png)

3. 실행
프로젝트에서 CMD 열기 -> sonar-scanner 명령어 실행
![image](https://user-images.githubusercontent.com/42139382/66747433-7f18b280-eebf-11e9-9f48-2a8fac9b1d80.png)
![image](https://user-images.githubusercontent.com/42139382/66747723-27c71200-eec0-11e9-8218-440f5ad2ac61.png)


4. 결과확인

# RedCA4D
  - 

# [1일차 설문](https://forms.gle/keskyey8C8DBXdA96)
- [결과]()

# [2일차 설문]()
- [결과]()

# [3일차 설문]()
- [결과]()

# [과정종료 조사]()
