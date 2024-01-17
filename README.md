
1. 개발환경세팅  
   1.1 JDK 1.8 설치 (완료)  
   1.2 Eclipse(201906버전), Spring 설치 (진행): 아직 STS 설치에 오류가 있는 것같습니다.  
   1.3 톰캣 설정 (완료)  
   1.4 Hello World 출력(진행,2024-01-17): MVC project가 보이지않습니다. ~~sts 설치에 문제가 있는 것 같아 해결중에 있습니다. 수동으로 설치해보고있습니다.~~  
   **sts 수동으로 설치해서 해당 실행파일로 들어가도 괜찮은지 궁금합니다! 사진과같이 들어갔습니다 ~~현재는 다음과같은 에러가 나오는 상태입니다~~**  
   <img width="481" alt="image" src="https://github.com/hyunjin-h/backend-assignment/assets/87686021/b6b8e897-c27c-47fa-b202-32c8919c75c0">

   sts.ini파일에 ```-vm C:\Program Files\Java\jdk1.8.0_211\jre\bin\java.exe```추가하여 문제해결했습니다. java version과 Spring version이 호환되지 않아 생기는 문제로 추측하고 있습니다.  
   참고자료: https://wiki.eclipse.org/Eclipse.ini  


