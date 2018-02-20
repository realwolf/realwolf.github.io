---
layout: post
title: "윈도우용 패키지 관리자 Chocolatey 설치하기"
description: "윈도우용 패키지 관리자 Chocolatey 설치하기"
categories: [manual]
tags: [chocolatey]
redirect_from:
  - /2017/09/08/
---


* Kramdown table of contents
{:toc .toc}


# 1. Chocolatey

윈도우용 패키지 관리자입니다.

[https://chocolatey.org/install](https://chocolatey.org/install)



# 2. 설치

파워쉘(Windows PowerShell)을 관리자 권한으로 실행한 다음 아래의 명령어를 입력합니다.

```
> Set-ExecutionPolicy AllSigned; iex ((New-Object System.Net.WebClient).DownloadString('https://chocolatey.org/install.ps1'))
```



# 3. 업그레이드

최신 버젼으로 업그레이드 하는 방법은 다음과 같습니다.

```
> choco upgrade chocolatey
```



# 4. 삭제

삭제와 관련해서는 공식사이트의 문서를 참고하시기 바랍니다.

[https://chocolatey.org/docs/uninstallation](https://chocolatey.org/docs/uninstallation)



# 5. 패키지 목록

[https://chocolatey.org/packages](https://chocolatey.org/packages)


<br>
