# Web Technology Profile Report

**Target:** `mail.proton.me`
**Report Date:** October 17, 2026
**Prepared by:** Lumo (Proton AI Assistant)
**Language:** English
**Report Status:** Partial — The primary source could not be retrieved, so an alternative source was used.

## 1. Scope

This report summarizes the web technology profile of `mail.proton.me` using technology detection services.

The original request was to collect technology data from the following Wappalyzer lookup page:

- <https://www.wappalyzer.com/lookup/mail.proton.me/>

Because the primary source could not be accessed successfully, BuiltWith was used as an alternative source.

## 2. Primary Source Retrieval Status

**Result:** FAILED

### Reason for Failure

Wappalyzer uses a single-page application (SPA) that loads its technology data dynamically through JavaScript.

Non-browser requests returned only an empty page structure along with an error message from Wappalyzer itself:

> Page not responding — Wappalyzer couldn't start in this browser. Reload the page or try disabling extensions.

No technology names could be extracted from the returned page.

### Attempts Made

- Retrieved `https://www.wappalyzer.com/lookup/mail.proton.me/`
- Retrieved `https://www.wappalyzer.com/lookup/mail.proton.me` without the trailing slash.
- Retrieved `https://www.wappalyzer.com/lookup/proton.me/`
- Searched the web for indexed Wappalyzer results.

### Important Note

No Wappalyzer technology data is included in this report because doing so without verifiable evidence would mean inventing results.

To obtain the actual Wappalyzer data, open the lookup page directly in a desktop browser. If necessary, temporarily disable extensions or ad blockers that may interfere with the page.

## 3. Alternative Data Source

**Source:** BuiltWith — a web technology profiling service with a purpose similar to Wappalyzer.

The following pages were successfully accessed:

- Subdomain-level profile: <https://builtwith.com/mail.proton.me>
- Parent-domain profile: <https://builtwith.com/proton.me>

The findings below are based on BuiltWith, not Wappalyzer. The two services may use different detection methods and report different results.

## 4. Findings for mail.proton.me

The following technologies were detected on the `mail.proton.me` subdomain.

### 4.1 Mobile Compatibility and Web App Features

| Technology | Purpose |
| --- | --- |
| Apple Mobile Web App Capable | Allows a web app to run in full-screen mode in Safari on iOS. |
| Apple Mobile Web App Status Bar Style | Controls the status bar appearance when an iOS web app is running. |
| Apple Mobile Web Clips Icon | Provides an icon for the website when added to the home screen on Apple mobile devices. |
| iPhone / Mobile Compatible | Indicates support for mobile content and devices. |
| Viewport Meta | Helps the page adapt to different screen sizes. |

### 4.2 Document Elements and Web Standards

| Technology | Purpose |
| --- | --- |
| HTML5 DocType | Declares the document as HTML5. |
| Cascading Style Sheets (CSS) | Defines the visual presentation and layout of web pages. |
| UTF-8 | Supports Unicode character encoding. |
| Canonical Content Tag | Identifies the preferred URL for search engines. |
| Meta Description | Provides a short description of the page for search engines and other services. |
| Open Graph Protocol | Defines metadata used to generate link previews on social platforms. |
| Twitter Cards | Provides rich link previews on X (formerly Twitter). |
| Web App Manifest | Defines metadata and behavior for an installable web app or Progressive Web App (PWA). |
| Subresource Integrity (SRI) | Allows browsers to verify the integrity of supported external resources. |
| JavaScript Defer | Delays script execution until the HTML document has been parsed. |
| DNS Prefetch | Attempts to resolve domain names in advance to reduce connection delays. |
| Windows 8 Pinning | Supports website pinning features in Windows 8. |
| Google No Translate | Discourages Google from offering automatic translation for the page. |

### 4.3 Infrastructure

| Finding | Description |
| --- | --- |
| Spanish Server Location | The profiling service identified Spain as the web server location. |

> **Analyst's note:** The reported Spanish server location may refer to a nearby CDN edge node rather than Proton's core infrastructure or primary data center. It should not be interpreted as definitive evidence of where Proton stores or processes its data.

## 5. Findings for the Parent Domain: proton.me

As of October 17, 2026, BuiltWith reported **183 active technologies** for `proton.me`, along with an **AI Index score of 91/100**.

The following is a partial list of technologies identified in the portions of the source page that could be accessed. It is not a complete inventory of all reported technologies.

### 5.1 Programming Languages and Frameworks

| Technology | Purpose |
| --- | --- |
| React | JavaScript library for building user interfaces. |
| React Native | Framework for developing mobile applications using React. |
| Node.js | JavaScript runtime commonly used for server-side applications. |
| Kotlin | Programming language used for Android and multiplatform development. |
| SwiftUI | Framework for building user interfaces across Apple platforms. |
| Jetpack Compose | Declarative UI toolkit for Android applications. |

### 5.2 Infrastructure and DevOps

| Technology | Purpose |
| --- | --- |
| Docker | Packages applications and their dependencies into containers. |
| Kubernetes | Automates container deployment, scaling, and management. |
| Argo CD | Supports GitOps-based continuous delivery. |
| Terraform | Defines and manages infrastructure through code. |
| Ansible | Automates system configuration and operational tasks. |
| Traefik | Reverse proxy and load balancer. |
| Linux | Operating system kernel widely used in server infrastructure. |
| GitLab and GitLab CI/CD | Supports source code management and automated build, test, and deployment pipelines. |
| GitHub | Platform for hosting code and collaborating on software development. |
| Playwright | Framework for automated end-to-end testing of web applications. |
| OWASP | Organization and collection of resources focused on application security. |

### 5.3 Observability and Data Technologies

| Technology | Purpose |
| --- | --- |
| Grafana | Visualizes metrics and monitoring data through dashboards. |
| Prometheus | Collects and stores time-series metrics for monitoring. |
| OpenTelemetry | Provides tools and standards for collecting telemetry data. |
| ClickHouse | Column-oriented database designed for analytical workloads. |
| Redis | In-memory data store commonly used for caching and other low-latency operations. |
| MongoDB | Document-oriented NoSQL database. |
| MySQL | Relational database management system. |
| Confluence | Collaboration and documentation platform. |

### 5.4 Artificial Intelligence

| Technology | Purpose |
| --- | --- |
| Mistral AI | Artificial intelligence company that develops AI models and related technologies. |
| MLOps | Practices and tools for deploying, managing, and maintaining machine learning systems. |

> **Important:** These detections do not necessarily mean that every listed technology is directly used by `mail.proton.me`. Some may belong to the broader `proton.me` domain, related services, or externally detected infrastructure. The profiling data alone does not establish the exact role of each technology.

## 6. Additional Context from Official Proton Sources

The following information comes from Proton's official blog and other cited sources. It is provided as additional context and should not be treated as a direct result of the BuiltWith scan.

### 6.1 Proton's Website Technology

According to Proton's official article, *How we built the Proton website*, Proton uses React for its web applications.

The article also describes the use of WordPress, PHP, and MySQL for its blog and support pages.

Source: <https://proton.me/blog/how-we-built-proton-website>

### 6.2 Proton Mail Mobile Applications

According to Proton's article, *Next-generation Proton Mail mobile apps*, the next-generation Proton Mail mobile applications were rewritten around a shared core implemented in Rust.

This core handles the applications' business logic. Proton also reported that approximately **80%** of the code could be reused across platforms.

Source: <https://proton.me/blog/next-generation-proton-mail-mobile-apps>

### 6.3 Open-Source Availability

According to the cited Wikipedia article, the source code for Proton Mail's web interface and its iOS and Android applications has been released as open source, while its backend remains closed source.

This statement reflects the cited source and should be independently verified against Proton's official repositories and current documentation.

Source: <https://en.wikipedia.org/wiki/Proton_Mail>

## 7. Report Limitations

The findings in this report have several important limitations.

- **Wappalyzer data was not obtained.** Sections 4 and 5 are based on BuiltWith, which uses its own detection methods. Its results cannot be treated as a direct replacement for Wappalyzer's results.
- **The parent-domain technology list is incomplete.** BuiltWith reported 183 active technologies for `proton.me`, but only a subset could be retrieved and included in this report.
- **The findings represent a point in time.** Web technology profiles can change as websites are updated, infrastructure evolves, and detection services refresh their data.
- **Automated infrastructure detection can be misleading.** For example, the reported Spanish server location may reflect a CDN edge location rather than Proton's primary infrastructure.
- **Individual findings have not been independently verified.** This report records findings attributed to the cited sources. It does not confirm that every detected technology is actively used by the target application.
- **Domain-level findings may not describe the target subdomain.** Technologies detected on `proton.me` may relate to other Proton services or infrastructure rather than `mail.proton.me` specifically.
- **Technology detection does not establish the internal architecture.** A detected framework, database, or infrastructure tool does not reveal how it is configured, where it is deployed, or which specific service uses it.

## 8. Recommended Next Steps

1. **Retrieve the Wappalyzer results directly.** Open <https://www.wappalyzer.com/lookup/mail.proton.me/> in a desktop browser. If the page fails to load, try disabling extensions or ad blockers. Export the results to CSV if the export feature is available with your Wappalyzer account.
2. **Compare Wappalyzer and BuiltWith.** Compare the two technology lists to identify differences in detection coverage and classification.
3. **Perform independent verification.** Inspect HTTP response headers, the web app manifest, publicly available frontend assets, and relevant open-source Proton repositories.
4. **Verify the scope of each technology.** Distinguish between technologies detected on `mail.proton.me`, those associated with the parent domain, and those reported for Proton's broader infrastructure.
5. **Use additional evidence for security assessments.** Public technology profiling tools should not be the sole basis for evaluating security. A meaningful assessment requires further evidence, appropriate testing, and, where possible, direct architectural review.

## 9. References

| No. | Source | Purpose | Status |
| --- | --- | --- | --- |
| 1 | <https://www.wappalyzer.com/lookup/mail.proton.me/> | Requested primary technology profile | Retrieval failed |
| 2 | <https://builtwith.com/mail.proton.me> | Subdomain-level technology profile | Retrieved |
| 3 | <https://builtwith.com/proton.me> | Parent-domain technology profile | Retrieved |
| 4 | <https://proton.me/blog/how-we-built-proton-website> | Official information about Proton's website technology | Retrieved |
| 5 | <https://proton.me/blog/next-generation-proton-mail-mobile-apps> | Official information about Proton Mail's mobile applications | Retrieved |
| 6 | <https://en.wikipedia.org/wiki/Proton_Mail> | Additional context on Proton Mail and its source code | Retrieved |

## Conclusion

This report provides a partial overview of the technologies associated with `mail.proton.me` and the broader `proton.me` domain, based primarily on BuiltWith.

Because the requested Wappalyzer data could not be retrieved, the findings should be treated as preliminary observations rather than a complete or independently verified technology inventory.

Further verification is needed to confirm the detected technologies, distinguish subdomain-specific findings from parent-domain findings, and establish a more reliable picture of Proton Mail's publicly observable web technology stack.

**End of Report**
