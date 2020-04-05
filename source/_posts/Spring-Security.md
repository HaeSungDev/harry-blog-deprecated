---
title: Spring Security 기본 개념
date: 2020-04-05 15:42:33
tags:
categories: [Spring, Spring Security]
---

## Spring Security

애플리케이션이나 웹에서 제공하는 서비스를 사용하기 위해 사용자는 회원 가입과 로그인을 합니다. 로그인을 한 후에는 권한이 있는 서비스를 사용하게 됩니다. 만약 로그인을 하지 않았거나 권한이 없다면 해당 서비스를 이용 할 수 없습니다.

이러한 과정은 크게 Authentication(인증), Authroization(인가)로 분류됩니다.

Authentication은 해당 사용자가 누구인지 확인하는 과정이고 Authorization은 사용자가 어떤 서비스나 리소스에 접근 할 수 있는 권한이 있는지 확인하는 과정입니다.

Authentication이나 Authorization은 웹이나 앱을 만드는 개발자가 직접 구현 할 수도 있지만 보안과 관련 되어있기 때문에 많은 사람들에게 검증되고 사용되는 라이브러리를 사용하는편이 더 안전합니다.

Spring에서 많이 사용되는 Authentication, Authorization 라이브러리 중 하나는 Spring Security입니다.

Spring Security는 Authentication(인증), Authorization(인가) 및 csrf 등의 공격을 막아주는 여러가지 기능을 제공합니다.
