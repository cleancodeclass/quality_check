## <strong>Quality Check</strong>
코드 품질 체크 Session


## SonarQube
- 다운로드
1. Server 다운로드 (https://binaries.sonarsource.com/Distribution/sonarqube/sonarqube-7.4.zip)
2. Client 다운로드 (https://binaries.sonarsource.com/Distribution/sonar-scanner-cli/sonar-scanner-cli-4.0.0.1744-windows.zip)
  
- Server 설치
1. 다운로드한 파일 압축풀기
2. 서버실행
	- StartSonar.bat 실행 (sonarqube-7.4\bin\windows-x86-64\StartSonar.bat)
	- 서버실행 확인 (http://localhost:9000)
	![image](https://user-images.githubusercontent.com/42139382/66746721-863ec100-eebd-11e9-9168-850c81d12d01.png)
	
Step 1. Client 설치
1. 다운로드한 파일 압축풀기
2. 환경변수 설정
3. 윈도우 cmd 에서 sonar-scanner 명령어 확인
![image](https://user-images.githubusercontent.com/42139382/66745823-09aae300-eebb-11e9-8b1b-5459567feefa.png)

Step 2. sonar-project.properties 파일 적용
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
![image](https://user-images.githubusercontent.com/42139382/66747917-b89ded80-eec0-11e9-9442-d7701114e38e.png)

4. 결과확인
![image](https://user-images.githubusercontent.com/42139382/66748019-07e41e00-eec1-11e9-8a2e-e69de9ed2440.png)

5. 대시보드 확인
![image](https://user-images.githubusercontent.com/42139382/66748279-bee09980-eec1-11e9-8481-d98765b6f122.png)

6. 상세지표 확인 (Cognitive Complexity)
![image](https://user-images.githubusercontent.com/42139382/66748469-3d3d3b80-eec2-11e9-8a4e-5b9bcda2106f.png)
![image](https://user-images.githubusercontent.com/42139382/66748573-74135180-eec2-11e9-8646-5a9f0574af7e.png)

7. 상세지표 확인 (검출룰셋 점검)
![image](https://user-images.githubusercontent.com/42139382/66748658-b5a3fc80-eec2-11e9-8b9f-7d5073679c40.png)
![image](https://user-images.githubusercontent.com/42139382/66748811-129fb280-eec3-11e9-8bcc-d0846507928c.png)

8. 상세지표 확인 (Measure)
![image](https://user-images.githubusercontent.com/42139382/66748963-7fb34800-eec3-11e9-8051-85ece701d4a5.png)



## RedCA4D
  - 
