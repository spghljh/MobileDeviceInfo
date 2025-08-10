# Changelog

## 애플리케이션 개요
애플리케이션 명칭 : MobileDeviceInfo
애플리케이션 유형 : PHP 웹 애플리케이션
기술 구성 : FastCGI 방식의 Non-Thread Safe PHP 8
데이터베이스 : MySQL 8
서버 구성 : Nginx 리버스 프록시 + Apache 기반 백엔드

## 2025-08-10
- `mdi1` 애플리케이션에 Nginx 리버스 프록시 적용 중.
- 현재는 `mdi1/index.php` 경로로만 접근 가능.
- 애플리케이션 내 상대 경로를 리버스 프록시에 맞게 수정 중.
