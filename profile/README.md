# Spring Academy Project

Spring Academy empowers Spring developers to continuously learn, innovate, and solve complex problems.

This repo documents the content catalog comprising Spring Academy,
and the locations where you can access the repositories hosting the content and lab configuration source.
It also documents where you can access the source and tools used by the lab environments.

## Accessing Spring Academy

Spring Academy is currently hosted and managed by [Broadcom](https://www.broadcom.com/) as a special developer portal.
Access and identity management are handled by [Broadcom Support](https://support.broadcom.com/).

You can register for and access Spring Academy [here](https://spring.academy).

## Course Catalog

This repository defines the tags, instructors, and learning paths for Spring Academy. The learning paths comprise a set of courses that you can find in the following repositories:

| Repo | Course(s) | Codebase | Status |
| ---- | --------- | -------- | ----------- |
| [course-spring-academy-sample](https://github.com/spring-academy/course-spring-academy-sample) | [Spring Academy Sample Course](https://spring.academy/courses/spring-academy-sample-course) | [Codebase](https://github.com/spring-academy/course-spring-academy-sample-code) | In Production (draft) |
| [course-spring-brasb-build-a-rest-api](https://github.com/spring-academy/course-spring-brasb-build-a-rest-api) | [Building a REST API with Spring Boot](https://spring.academy/courses/building-a-rest-api-with-spring-boot) |[Codebase](https://github.com/spring-academy/course-spring-brasb-build-a-rest-api-code) | In Production (live) |
| [course-spring-professional](https://github.com/spring-academy/course-spring-professional) | <ul><li>[Introduction to the Spring Professional Learning Path](https://spring.academy/courses/spring-introduction)</li><li>[Spring Framework Essentials](https://spring.academy/courses/spring-framework-essentials)</li><li>[Spring Boot](https://spring.academy/courses/spring-boot)</li></ul> | [Codebase](https://github.com/spring-academy/spring-pro-code) | In Production (live) |
| [course-spring-batch](https://github.com/spring-academy/course-spring-batch) | [Spring Batch Essentials](https://spring.academy/courses/spring-batch-essentials) | [Codebase](https://github.com/spring-academy/course-spring-batch-essentials-code) | In Production (live) |
| [course-spring-boot-native](https://github.com/spring-academy/course-spring-boot-native) | [Building Native Applications with Spring Boot and GraalVM](https://spring.academy/courses/spring-boot-native) | [Codebase](https://github.com/spring-academy/course-spring-boot-native-code) | In Production (live-pro) |
| [course-secure-rest-api-oauth2](https://github.com/spring-academy/course-secure-rest-api-oauth2) | [Securing a REST API with OAuth 2.0](https://spring.academy/courses/spring-academy-secure-rest-api-oauth2) | [Codebase](https://github.com/spring-academy/course-secure-rest-api-oauth2-code) | In Production (live) |
| [course-spring-boot-2-5-to-2-7-upgrade](https://github.com/spring-academy/course-spring-boot-2-5-to-2-7-upgrade) | [Upgrading from Spring Boot 2.5 to 2.7](https://spring.academy/courses/spring-boot-2-5-to-2-7-upgrade) | [Codebase](https://github.com/spring-academy/course-spring-boot-2-5-to-2-7-upgrade-code) | In Production (live-pro) | [Upgrading from Spring Boot 2-7-to-3-1](https://spring.academy/courses/spring-boot-2-7-to-3-1-upgrade)|
| [course-spring-boot-2-7-to-3-1-upgrade](https://github.com/spring-academy/course-spring-boot-2-7-to-3-1-upgrade) | [Upgrading from Spring Boot 2.7 to 3.1](https://spring.academy/courses/spring-boot-2-7-to-3-1-upgrade) | [Codebase](https://github.com/spring-academy/course-spring-boot-2-7-to-3-1-upgrade-code) | In Production (live-pro) |
| [course-spring-cloud-stream](https://github.com/spring-academy/course-spring-cloud-stream) | [Spring Cloud Stream](https://spring.academy/courses/spring-cloud-stream) | [Codebase](https://github.com/spring-academy/course-spring-cloud-stream-code) | In Production (live) |

## Guides

[Guides]((https://spring.academy/guides)) are standalone lessons, mostly consisting of Educate labs.

They are organized by author-curated repos:

- Spring Guides (Upgrade, Modulith): [spring-guides](https://github.com/spring-academy/spring-guides)
- Spring Engineering Guides (Spring Engineering Focused): [spring-engineering-guides](https://github.com/spring-academy/spring-engineering-guides)
- Spring IO Guides (early effort to give labs experience to Spring IO guides, deprecated): [spring-io-guides](https://github.com/spring-academy/spring-io-guides)
- Tanzu Developer Center Spring Guides (deprecated): [spring-tdc-guides](https://github.com/spring-academy/spring-tdc-guides)
## Tools

Various tools are required to either deploy content or labs,
and some cases, labs require special tooling.

The following are references for the repos including the various tools:

- [Metadata](https://github.com/spring-academy/spring-academy-meta): Necessary for deployment to Broadcom Support Portal
- [Tools](https://github.com/spring-academy/spring-academy-tools): Various tools used by the labs
- [Extension Packages](https://github.com/spring-academy/spring-academy-extension-packages): Used by the labs for coordinating codebase checkouts
- [Github Actions](https://github.com/spring-academy/spring-academy-github-actions): Used for publishing workshop packages used by the labs

## Permissions and Support

While you have access to peruse the content and lab source materials in this project on Github,
if you are perusing [Spring Academy](https://spring.academy),
you may notice you do not have access to some of the courses.

The following are some general rules that apply according to the status indicated to the courses above:

- *Live*: public access, all registered Spring Academy users can access.
- *Draft*: only Broadcom internal admin / authors can access.
- *Live-pro*: public access for users with registered work email addresses.

You can contact the Spring Academy support team at spring.academy@broadcom.com
if you have questions or need support.

## Contributing a Course

We are not currently accepting external contributions for new content, but feel free to give feedback on existing content.  See our [Contribution Guide](../CONTRIBUTING.md).

## Authoring Guidelines

See the [authoring guidelines](../docs/lab-authoring-style-guide.md)
used for a large segment of the course repositories.

See the [labs authoring guidelines](../docs/authoring-labs.md)
that the authors used to author, test and run educates lab workshops.
