
# 1. 개발환경세팅  
## 1.1 JDK 1.8 설치 (완료)  
JAVA 1.8.0_8u221
## 1.2 Eclipse, Spring 설치 (완료)
Eclipse: 2019-06  
Spring: STS 3.9.11  
## 1.3 톰캣 설정 (완료)
apache-tomcat-9.0.85
## 1.4 Hello World 출력(완료)
~~MVC project가 보이지않습니다.~~(→ sts3.9.11 수동설치)  
**(sts 수동으로 설치해서 해당 실행파일(STS.exe)로 진행해도 괜찮은지 궁금합니다!)**    
> ERROR: Could not initialize class com.thoughtworks.xstream.converters.collections.PropertiesConverter

sts.ini파일에 ```-vm C:\Program Files\Java\jdk1.8.0_211\jre\bin\java.exe```추가하여 문제해결했습니다. java version과 Spring version이 호환되지 않아 생기는 문제로 추측하고 있습니다.  
참고자료: https://wiki.eclipse.org/Eclipse.ini  

<img width="336" alt="image" src="https://github.com/hyunjin-h/backend-assignment/assets/87686021/0d6760aa-5a75-4c0c-b06b-aaf5296ab2d3">  

## 1.5 mariadb, mySql Workbench 설치 및 샘플 DB 구축(완료)
mariadb: 10.2.14  
mySql Workbench: 8.0.31  
<img width="196" alt="image" src="https://github.com/hyunjin-h/backend-assignment/assets/87686021/e83d2a28-8d72-48c0-83f4-07649f2cf86e">  
## 1.6. 스프링, Mariadb, MyBatis 연동, 데이터 조회(진행)






