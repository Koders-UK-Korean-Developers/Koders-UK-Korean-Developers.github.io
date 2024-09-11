# UDG 웹사이트

이 웹사이트는 [Hugo](https://gohugo.io/)를 사용하여 제작된 정적 사이트입니다. Hugo는 빠르고 유연한 정적 사이트 생성기로, 이 사이트는 마크다운으로 작성되었으며 GitHub Actions를 통해 배포됩니다.

이 웹사이트는 UDG 카카오톡 그룹에서 공유된 유용한 정보를 저장하고 공유하기 위한 목적으로 만들어졌습니다. 더 자세한 정보나 문의 사항이 있으시면 UDG 카카오톡 오픈채팅방에 참여해 주세요: [여기](https://open.kakao.com/o/gZ8vLKsf)에서 참여할 수 있습니다.

## 목차
- [웹사이트 개요](#웹사이트-개요)
- [시작하기](#시작하기)
- [테마](#테마)
- [배포](#배포)
- [기여하기](#기여하기)
- [라이선스](#라이선스)
- [ETC](#ETC)

## 웹사이트 개요
이 웹사이트는 Hugo와 [GeekDocs](https://geekdocs.de/) 테마를 사용하여 제작되었습니다. 빠르고, 접근성이 뛰어나며, 관리가 간편하도록 설계되었습니다. 개인 블로그, 프로젝트 문서화, 정적 콘텐츠 관리 등 다양한 용도로 사용할 수 있습니다.

주된 목적은 UDG 카카오톡 그룹에서 공유된 귀중한 정보를 저장하고 이를 더 많은 사람들과 나누는 것입니다.

## 시작하기

이 Hugo 웹사이트를 시작하려면 다음 단계를 따르세요:

1. **Hugo 설치**: 
   먼저 로컬 환경에 Hugo를 설치해야 합니다. [Hugo 설치 가이드](https://gohugo.io/getting-started/installing/)를 참고하여 설치를 완료하세요.
   
2. **저장소 클론**:
   ```bash
   git clone https://github.com/your-username/your-repo.git
   cd your-repo
   ```

3. **로컬 서버 실행**:
   ```bash
   hugo server
   ```

## 테마

이 프로젝트는 [GeekDocs 테마](https://geekdocs.de/)를 사용하고 있습니다. 테마에 대한 자세한 문서 및 커스터마이징 방법은 [테마 공식 사이트](https://geekdocs.de/)에서 확인할 수 있습니다.

테마를 수정하거나 업데이트하려면 `themes` 디렉토리에서 필요한 변경 사항을 적용하세요. 또한 `assets` 디렉토리에서 사용자 정의 CSS와 JS 파일을 추가할 수 있습니다.

## 배포

이 웹사이트는 GitHub Actions를 통해 자동으로 배포됩니다. 메인 브랜치에 푸시될 때마다 GitHub Pages로 자동 배포가 이루어집니다.

GitHub에 Hugo 웹사이트를 배포하는 방법에 대한 자세한 내용은 [Hugo 공식 문서](https://gohugo.io/hosting-and-deployment/hosting-on-github/)를 참조하세요.

### GitHub Actions

이 저장소는 `.github/workflows/deploy.yml`에 정의된 GitHub Actions 워크플로우를 사용하여 사이트를 빌드하고 배포합니다. 이 워크플로우는 Hugo를 사용해 사이트를 빌드한 후 배포합니다.

배포 상태는 저장소의 "Actions" 탭에서 확인할 수 있습니다.

## 기여하기

기여는 언제나 환영입니다! 웹사이트 개선에 기여하고 싶으시다면, 저장소를 포크한 후 새로운 기능 브랜치를 생성하고 풀 리퀘스트를 보내주세요.

### 기여 방법:
```bash
1. 저장소를 포크하세요.
2. 새로운 브랜치를 생성하세요 (`git checkout -b feature-branch`).
3. 변경 사항을 커밋하세요 (`git commit -m 'Add some feature'`).
4. 브랜치에 푸시하세요 (`git push origin feature-branch`).
5. 풀 리퀘스트를 열어주세요.
```

## 라이선스
이 프로젝트는 MIT 라이선스를 따릅니다.


## ETC

추가 질문이나 토론에 참여하고 싶으시다면 UDG 카카오톡 오픈채팅방에 참여해 주세요: [여기](https://open.kakao.com/o/gZ8vLKsf)에서 참여할 수 있습니다.


---

# UDG Website (English)

This is a static website built using [Hugo](https://gohugo.io/), a fast and flexible static site generator. The site is written in Markdown and deployed using GitHub Actions.

This website is designed to store and share valuable information that has been discussed and shared in the UDG KakaoTalk group. For more detailed information or any inquiries, you can join the UDG KakaoTalk Open Chat [here](https://open.kakao.com/o/gZ8vLKsf).

## Table of Contents
- [Website Overview](#website-overview)
- [Getting Started](#getting-started)
- [Theme](#theme)
- [Deployment](#deployment)
- [Contributing](#contributing)
- [License](#license)
- [ETC](#ETC)

## Website Overview
This website is powered by Hugo and uses the [GeekDocs](https://geekdocs.de/) theme. It is designed to be fast, accessible, and simple to manage. You can use it for personal blogs, project documentation, or any other static content.

The website’s main purpose is to serve as a repository for valuable insights and information shared in the UDG KakaoTalk group.

## Getting Started

To get started with this Hugo website, follow these steps:

1. **Install Hugo**: 
   You need to have Hugo installed on your local machine. You can follow the [Hugo installation guide](https://gohugo.io/getting-started/installing/) to set it up.
   
2. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/your-repo.git
   cd your-repo
   ```

3. **Run this site locally**:
   ```bash
   hugo server
   ```

## Theme

This project uses the [GeekDocs theme](https://geekdocs.de/). You can find detailed documentation and customization options on the [official theme website](https://geekdocs.de/).

To update or modify the theme, go to the `themes` directory and make any necessary changes. You can also add custom CSS and JS files in the `assets` directory.

## Deployment

The site is automatically deployed via GitHub Actions. Every push to the main branch triggers a new deployment to GitHub Pages.

For more information on hosting a Hugo website on GitHub, refer to the [official Hugo documentation](https://gohugo.io/hosting-and-deployment/hosting-on-github/).

### GitHub Actions

This repository uses a GitHub Actions workflow defined in `.github/workflows/deploy.yml` to build and deploy the site. The workflow builds the site using Hugo and then deploys it.

You can view the status of the deployment under the "Actions" tab of this repository.

## Contributing

Contributions are welcome! If you want to improve the website, feel free to fork this repository, create a feature branch, and submit a pull request.

### Steps to Contribute:
```bash
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a pull request.
```

## License
This project is licensed under the MIT License.

## ETC

For further questions or to join the discussion, please join the UDG KakaoTalk Open Chat [here](https://open.kakao.com/o/gZ8vLKsf).