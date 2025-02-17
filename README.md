# 프론트엔드 배포 파이프라인

## 개요

GitHub Actions에 워크플로우를 작성해 다음과 같이 배포가 진행됩니다.

1. 저장소를 체크아웃합니다.
2. Node.js 18.20.6(LTS) 버전을 설정합니다.
3. 프로젝트 의존성을 설치합니다.
4. Next.js 프로젝트를 빌드합니다.
5. AWS 자격 증명을 구성합니다.
6. 빌드된 파일을 S3 버킷에 동기화합니다.
7. CloudFront 캐시를 무효화합니다.

## 주요 링크

- S3 버킷 웹사이트 엔드포인트: http://hanghae-plus-4-1.s3-website-us-east-1.amazonaws.com
- CloudFrount 배포 도메인 이름: https://d346v5hpog4fqr.cloudfront.net

## 주요 개념

- GitHub Actions과 CI/CD 도구: \***\*\_\*\***
- S3와 스토리지: \***\*\_\*\***
- CloudFront와 CDN: \***\*\_\*\***
- 캐시 무효화(Cache Invalidation): \***\*\_\*\***
- Repository secret과 환경변수: \***\*\_\*\***

## CDN과 성능최적화

- (CDN 도입 전과 도입 후의 성능 개선 보고서 작성)
