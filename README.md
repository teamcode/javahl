# Apache Subversion JavaHL
[![Download](https://api.bintray.com/packages/teamcode/maven/javahl/images/download.svg) ](https://bintray.com/teamcode/maven/javahl/_latestVersion)

이 프로젝트는 Apache Subversion 프로젝트에서 제공하는 JavaHL 소스 코드를
JAR 파일로 빌드하고 Bintray 에 호스팅하여 공유할 수 있도록 만든 것입니다.
원본 소스 코드에 대한 어떠한 변경이 없으며 라이선스도 Apache Subversion JavaHL 의 것을 그대로 따릅니다.

## 빌드 및 배포
gradle 명령어로 아래와 같이 빌드 후 배포합니다.
```
gradle -Pkey=[bintray-api-key] bintrayUpload -x test
```

테스트를 위해서는 Subversion Client 1.9.x 를 설치해야 하므로
설치가 어렵거나 테스트가 필요없다고 생각하면 위에서처럼 Test 를 무시하고 빌드를 하면 됩니다.

Bintray 서비스를 통해 Library를 공유할 수 있도록 설정했습니다. Bintray 계정을 만들고 설정 후 API Key 를 사용해서 배포해 보세요.
