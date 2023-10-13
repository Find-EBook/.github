## `.github` 레포지토리 안내서

### 1. `.github` 레포지토리란?

`.github` 레포지토리는 GitHub 조직 내의 모든 레포지토리에 대한 기본 설정, 파일 및 워크플로우를 저장하는데 사용됩니다. 이것은 특히 팀이나 조직의 여러 레포지토리에 걸쳐 일관된 설정이나 워크플로우를 가지고 싶을 때 유용합니다.

### 2. 어디에 사용되나요?

`.github` 레포지토리에 저장된 설정과 파일은 다음과 같은 경우에 사용될 수 있습니다:

1. **Issue & Pull Request 템플릿**: 사용자들이 이슈나 PR을 생성할 때 안내를 받게 도와줍니다.
2. **Actions 워크플로우**: GitHub Actions 워크플로우 설정을 저장하고 조직 전체에 적용할 수 있습니다.
3. **CODEOWNERS 파일**: 특정 폴더나 파일에 대한 코드 소유자를 지정하여 PR이나 변경사항이 있을 때 알림을 받을 수 있게 합니다.
4. **Contributing 가이드라인**: 프로젝트에 기여할 때 준수해야 할 가이드라인을 제시합니다.

### 3. 어떻게 사용하나요?

1. **Issue & Pull Request 템플릿 생성**:
   - `.github/ISSUE_TEMPLATE` 및 `.github/PULL_REQUEST_TEMPLATE` 디렉토리를 만듭니다.
   - 이 디렉토리 내에 원하는 템플릿 파일들을 생성합니다. 예: `bug_report.md`, `feature_request.md` 등.

2. **Actions 워크플로우 설정**:
   - `.github/workflows` 디렉토리 내에 워크플로우 yml 파일을 생성합니다.
   - 워크플로우에 대한 설정 및 단계를 해당 파일에 정의합니다.

3. **CODEOWNERS 파일 설정**:
   - `.github/CODEOWNERS` 파일을 생성합니다.
   - 특정 폴더나 파일에 대한 코드 소유자를 지정합니다. 예: `/docs/ @documentation-team`

4. **Contributing 가이드라인 설정**:
   - `.github/CONTRIBUTING.md` 파일을 작성하여 기여 가이드라인을 정의합니다.

### 4. 결론

`.github` 레포지토리는 조직의 여러 레포지토리에 공통적으로 적용되는 설정 및 파일을 중앙에서 관리하는 데 유용합니다. 잘 설정된 `.github` 레포지토리를 통해 조직의 개발 및 협업 프로세스를 효율적으로 관리할 수 있습니다.
