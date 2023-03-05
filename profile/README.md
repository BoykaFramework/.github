<div align="center">

  <img src="assets/Boyka.png" alt="logo" width="200" height="auto" />

  <h2>
    🎉 Ultimate test automation for testing any application on any platform
  </h2>
  <h3>
    Don't forget to ⭐ the repository if you like it!
  </h3>

<!-- Badges -->
<p>

[![Product Hunt](https://api.producthunt.com/widgets/embed-image/v1/featured.svg?post_id=352770&theme=light)](https://www.producthunt.com/posts/boyka-framework?utm_source=badge-featured&utm_medium=badge&utm_souce=badge-boyka-framework)

[![Open in GitPod](https://gitpod.io/button/open-in-gitpod.svg)](https://gitpod.io/#https://github.com/BoykaFramework/boyka-framework)

  <a href="https://discord.gg/dUg8K9DAsR">
    <img src="https://img.shields.io/discord/950985052769120337?label=Discord&logo=Discord&style=for-the-badge" alt="Join Discord">
  </a>
  <a href="https://github.com/BoykaFramework/boyka-framework/graphs/contributors">
    <img src="https://img.shields.io/github/contributors/BoykaFramework/boyka-framework?style=for-the-badge" alt="contributors" />
  </a>
  <a href="https://github.com/BoykaFramework/boyka-framework/commits/main">
    <img src="https://img.shields.io/github/last-commit/BoykaFramework/boyka-framework?style=for-the-badge" alt="last update" />
  </a>
  <a href="https://mvnrepository.com/artifact/com.github.wasiqb.boyka/boyka-framework">
    <img src="https://img.shields.io/maven-central/v/com.github.wasiqb.boyka/boyka-framework.svg?style=for-the-badge" alt="Maven Central" />
  </a>
  <a href="https://github.com/BoykaFramework/boyka-framework/releases/tag/v0.13.0">
    <img src="https://img.shields.io/github/downloads/BoykaFramework/boyka-framework/v0.13.0/total?color=brightgreen&label=Downloads%20for%20v0.13.0&logo=GitHub&style=for-the-badge" alt="GitHub releases" />
  </a>
  <a href="https://github.com/BoykaFramework/boyka-framework/blob/master/LICENSE">
    <img src="https://img.shields.io/github/license/BoykaFramework/boyka-framework.svg?style=for-the-badge" alt="license" />
  </a>
</p>

  <h4>
    <a href="https://boykaframework.github.io/boyka-framework/docs/intro">Documentation</a>
  <span> | </span>
    <a href="https://github.com/BoykaFramework/boyka-framework/issues/new/choose">Report Bug</a>
  <span> | </span>
    <a href="https://github.com/BoykaFramework/boyka-framework/issues/new/choose">Request Feature</a>
  </h4>
</div>

<br />

## 🤔 Why was Boyka-framework created?

In my career having vast experience in automating API, Web browsers and Mobile apps, I have seen that people had to use different frameworks for automating API, Web and Mobile applications which created a lot of chaos with respect to maintenance of dependencies and their respective code for test automation.

Also, I never came across a test automation framework which allowed us to write automation test script without any project specific boilerplate code or a mini framework.

In addition to this, there was learning curve involved for learning those individual frameworks which slowed down the team to write automation and thus increased overall automation debt.

This all gave me an idea of having a single framework which could solve all the above mentioned problems and help the QA's to keep the pace up with writing test scripts and reduce the automation debt.

## 🎯 Features

- ✅ Zero boilerplate code
- ✅ Support Rest API automation with schema validations and response body verification
- ✅ Supports Web browser automation with support for Chrome, Edge, Firefox and Safari.
- ✅ Supports Android native apps automation
- ✅ Supports iOS native apps automation
- ✅ Supports execution of Web tests on cloud platforms like BrowserStack and LambdaTest.
- ✅ Highly configurable via `boyka-config.json`
- ✅ Micro logging to log events of the test execution
- ✅ Supports taking screenshots

## ⏱️ Coming soon

Following are the awesome features which will be implemented soon to the frameworks:

- Support for GraphQL and SOAP API automation
- Support video recording of the tests for Web and Mobile platforms
- Support for more cloud platforms.
- Many many more...

## 👀 Usage

Use this space to tell a little more about your project and how it can be used. Show additional screenshots, code samples, demos or link to other resources.

```xml
<dependency>
  <groupId>com.github.wasiqb.boyka</groupId>
  <artifactId>boyka-framework</artifactId>
  <version>0.13.0</version>
</dependency>
```

## ☕ Examples

- API:
  - [How to configure Boyka for API Automation?](https://boykaframework.github.io/boyka-framework/docs/guides/api/setup-config)
  - [How to compose a request?](https://boykaframework.github.io/boyka-framework/docs/guides/api/compose-request)
  - [How to execute a request?](https://boykaframework.github.io/boyka-framework/docs/guides/api/execute-request)
  - [How to verify the response?](https://boykaframework.github.io/boyka-framework/docs/guides/api/verify-response)
- UI:
  - Web:
    - [How to configure Boyka for Web Automation?](https://boykaframework.github.io/boyka-framework/docs/guides/ui/web/setup-config)
    - [How to create page object for Web?](https://boykaframework.github.io/boyka-framework/docs/guides/ui/web/create-page-object)
  - Android:
    - [How to configure Boyka for Android Automation?](https://boykaframework.github.io/boyka-framework/docs/guides/ui/android/setup-config)
    - [How to update existing page object with Android locators?](https://boykaframework.github.io/boyka-framework/docs/guides/ui/android/create-page-object)
  - iOS:
    - [How to configure Boyka for iOS Automation?](https://boykaframework.github.io/boyka-framework/docs/guides/ui/ios/setup-config)
    - [How to update existing page object for iOS locators?](https://boykaframework.github.io/boyka-framework/docs/guides/ui/ios/create-page-object)
  - [How to create common application action class?](https://boykaframework.github.io/boyka-framework/docs/guides/ui/page-action)
  - [How to write test class using common action class?](https://boykaframework.github.io/boyka-framework/docs/guides/ui/write-test)

## 💎 Cloud platform supporters

Big thanks to the following organizations for their support to the project with their open source licenses:

<div align="center">
  <a href="http://www.lambdatest.com?fp_ref=wasiq95" target="_blank" style="outline:none;border:none;"><img src="https://d2gdx5nv84sdx2.cloudfront.net/uploads/n3ufe5o3/marketing_asset/banner/6476/728_x_90.png" alt="lambdatest"/></a>
  <br/>
  <a href="http://www.browserstack.com" target="_blank" style="outline:none;border:none;"><img src="./website/static/img/docs/community/our-supporters/browser-stack.png" alt="browserstack"/></a>
</div>

## 🧭 Project Road-map

Following is the framework design for it's initial MVP:

![Boyka framework design](assets/Boyka-Framework.png)

Check out our road map to know which features we are cooking,

- [Project Road-map](https://github.com/orgs/BoykaFramework/projects/4/views/1)
- [Current Milestone](https://github.com/orgs/BoykaFramework/projects/4/views/2)
- [Next Milestone](https://github.com/orgs/BoykaFramework/projects/4/views/3)
- [Future planned features](https://github.com/orgs/BoykaFramework/projects/4/views/4)

## 🤝 Contact

- Join our [Discord server](https://discord.gg/dUg8K9DAsR) to discuss anything about the framework
- Open a [new Discussion](https://github.com/BoykaFramework/boyka-framework/discussions/new) on GitHub to ask questions or to discuss ideas
- Connect with me on [my LinkFree links](https://linkfree.eddiehub.io/WasiqB)
