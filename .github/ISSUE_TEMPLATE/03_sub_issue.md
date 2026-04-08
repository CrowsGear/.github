---
name: "✨ SUB ISSUE"
about: 새로운 기능 구현 또는 업무 단위 이슈
title: "[] "
labels:
assignees: []
---

## 📋 개요 (Required)

- 구현하고자 하는 기능을 설명해주세요.

## 📝 상세 내용 (Optional)

- 구현 방식, 고려 사항 등을 적어주세요.

## ✅ 마감 전 체크 (Checklist)

- [ ] 작업 내용 - LABEL 일치 여부 확인

## 정책

1. 브랜치 명명 방식 : `{Label}/{이니셜}/{Parent Brance Name}-{...}` (예시 참고)
2. Issue title [] 내 등록한 labels 입력(FEATURE, MODIFY, ... 등)
3. Parent Branch 병합 시 `Squash and Merge` 사용
4. 개인 작업 용

```
[예시]
Parent Issue/Branch : "auth"
- feature/bbi/auth-login-form
- modify/bbi/auth-login-form-component
```
