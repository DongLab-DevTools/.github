# [Project Name]
<!-- 📝 프로젝트 이름을 입력하세요 (예: ScreenNameViewer-For-Compose) -->

[![Hits](https://myhits.vercel.app/api/hit/https%3A%2F%2Fgithub.com%2F[USERNAME]%2F[REPOSITORY]%3Ftab%3Dreadme-ov-file?color=blue&label=hits&size=small)](https://myhits.vercel.app)
[![Platform](https://img.shields.io/badge/platform-Android-3DDC84?style=flat-square&logo=android)](https://developer.android.com)
[![Min SDK](https://img.shields.io/badge/min%20sdk-21-green?style=flat-square)](https://developer.android.com)
[![Jitpack](https://jitpack.io/v/[USERNAME]/[REPOSITORY].svg)](https://jitpack.io/#[USERNAME]/[REPOSITORY])
<!-- 📝 [USERNAME]과 [REPOSITORY]를 실제 GitHub 계정과 저장소 이름으로 변경하세요 -->

**[한국어 README](./README_ko.md)**

## Overview
<!-- 📝 프로젝트 개요 작성 가이드:
- 프로젝트가 무엇인지 간단히 설명
- 주요 목적과 해결하는 문제 설명
- 2-3문장으로 핵심 내용 요약
예시: "ScreenNameViewer is a debugging tool that overlays the class name of the currently displayed screen." -->

![sample]([IMAGE_PATH])
<!-- 📝 프로젝트 스크린샷이나 데모 이미지 경로 입력 
예시: https://github.com/USERNAME/REPO/blob/main/.github/docs/images/sample.png -->

<a href="[RELATED_PROJECT_URL]">
	<img src="[THUMBNAIL_IMAGE_PATH]"/>
</a>
<!-- 📝 관련 프로젝트가 있다면 링크와 썸네일 이미지 추가 (선택사항) -->

<br>
<br>

[Project description - 2-3 sentences explaining what the project does and why it's useful]
<!-- 📝 프로젝트 상세 설명:
예시: "It allows you to intuitively check which screen is active, and in a Compose environment, it can also display the screen route.
This allows you to quickly find and navigate to the code for the desired screen, improving both debugging and development efficiency." -->

<br>

## Features
<!-- 📝 주요 기능 나열 가이드:
- 각 기능마다 **굵은 제목**과 간단한 설명 작성
- 기술적 특징이나 장점 위주로 작성
- 3-6개 정도의 핵심 기능 나열
예시 형식:
- **Real-time class name display**: Shows Activity and Fragment class names on screen in real-time
- **Automatic lifecycle management**: Automatically tracks all Activities and Fragments at the Application level
-->

- **[Feature 1 Title]**: [Feature description]
- **[Feature 2 Title]**: [Feature description]
- **[Feature 3 Title]**: [Feature description]
- **[Feature 4 Title]**: [Feature description]
- **[Feature 5 Title]**: [Feature description]
- **[Feature 6 Title]**: [Feature description]

<br>

## Installation

### Step 1: Add Jitpack repository

Add the Jitpack repository to your project's `settings.gradle.kts`:

```kotlin
dependencyResolutionManagement {
    repositories {
        google()
        mavenCentral()
		maven { url = uri("https://jitpack.io") }
    }
}
```

### Step 2: Add dependency

Add the library to your module's `build.gradle.kts`:

```kotlin
dependencies {
    implementation 'com.github.[USERNAME]:[REPOSITORY]:latestVersion'
}
```
<!-- 📝 [USERNAME]과 [REPOSITORY]를 실제 값으로 변경하세요 -->

<br>

### Requirements
<!-- 📝 요구사항 작성 가이드:
- 최소 Android API 레벨
- 필수 라이브러리나 의존성
- 필요한 권한
예시:
- Android API 21 (Android 5.0) or higher
- Kotlin 1.9.0 or higher
-->

- [Requirement 1]
- [Requirement 2]

<br>

## Usage
<!-- 📝 사용법 작성 가이드:
- 기본적인 초기화 및 설정 방법 제시
- 실제 동작하는 코드 예시 작성
- 필수 설정과 선택적 설정 구분
- 주석으로 각 부분 설명 추가
-->

### [Section Title - e.g., "Initialize in Application class"]
<!-- 📝 각 사용 단계별 제목 작성 
예시: "Initialize in Application class", "Basic Setup", "Add to NavHost" -->

```kotlin
// 📝 실제 사용 가능한 코드 예시 작성
// 예시:
class MyApplication : Application() {
    override fun onCreate() {
        super.onCreate()
        
        initYourLibrary(this) {
            // Configuration
        }
    }
}
```

### [Additional Section Title - Optional]
<!-- 📝 추가 설정이나 고급 사용법이 있다면 작성 -->

```kotlin
// 📝 추가 사용 예시
```

<br>

## Configuration
<!-- 📝 설정 옵션 작성 가이드:
- DSL이나 설정 방법 상세 설명
- 각 설정 옵션의 의미와 사용법
- 기본값과 가능한 값 범위 명시
-->

### DSL Configuration
<!-- 📝 전체 설정 예시를 하나의 코드 블록으로 작성 -->

```kotlin
// 📝 실제 설정 가능한 DSL 예시 작성
// 예시:
initYourLibrary(this) {
    settings {
        option1 = value1  // Description
        option2 = value2  // Description
    }
    
    config {
        section1 {
            property1 = value1  // Description
            property2 = value2  // Description
        }
    }
}
```

<br>

### Configuration Options
<!-- 📝 각 설정 옵션 상세 설명:
- 설정 카테고리별로 그룹화
- 각 옵션의 역할과 가능한 값 설명
- 기본값 명시
예시:
- **settings**: Configure activation conditions
  - `debugModeCondition`: Debug mode condition (default: BuildConfig.DEBUG)
  - `enableCondition`: Overlay feature activation condition
-->

- **[Settings Category 1]**: [Category description]
  - `[option1]`: [Option description, possible values, default value]
  - `[option2]`: [Option description, possible values, default value]

- **[Settings Category 2]**: [Category description]
  - `[option3]`: [Option description, possible values, default value]
  - `[option4]`: [Option description, possible values, default value]

<br>

## Contributors
<!-- 📝 기여자 정보 입력:
- GitHub 사용자명과 프로필 이미지 URL 입력
- 실제 이름 입력
- 기여자가 추가되면 테이블에 <td> 항목 추가
-->

<!-- readme: collaborators,contributors -start -->
<table>
	<tbody>
		<tr>
            <td align="center">
                <a href="https://github.com/[USERNAME1]">
                    <img src="https://avatars.githubusercontent.com/u/[USER_ID]?v=4" width="100;" alt="[USERNAME1]"/>
                    <br />
                    <sub><b>[Full Name]</b></sub>
                </a>
            </td>
            <td align="center">
                <a href="https://github.com/[USERNAME2]">
                    <img src="https://avatars.githubusercontent.com/u/[USER_ID]?v=4" width="100;" alt="[USERNAME2]"/>
                    <br />
                    <sub><b>[Full Name]</b></sub>
                </a>
            </td>
		</tr>
	<tbody>
</table>
<!-- readme: collaborators,contributors -end -->
