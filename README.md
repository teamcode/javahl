# Apache Subversion JavaHL
[![Build Status](https://travis-ci.org/subclipse/javahl.svg?branch=master)](https://travis-ci.org/subclipse/javahl)
[![Download](https://api.bintray.com/packages/teamcode/maven/javahl/images/download.svg) ](https://bintray.com/teamcode/maven/javahl/_latestVersion)

This is just a copy of the upstream source code so that we can build
and publish the JAR to a Maven repository which we are hosting at Bintray.

# 빌드 및 배포
gradle 명령어로 아래와 같이 빌드 후 배포합니다.
```
gradle -Pkey=[bintray-api-key] bintrayUpload -x test
```

Bintray 서비스를 통해 Library를 공유할 수 있도록 설정했습니다. Bintray 계정을 만들고 설정 후 API Key 를 사용해서 배포해 보세요.
