# V8 CVEs 2010

- CVEs: 3
- [json](2010.json)

| CVE | Issue | Impact | ITW | Fix | Chrome release |
| --- | --- | --- | --- | --- | --- |
| CVE-2010-1506 | [40635](https://issues.chromium.org/issues/40635) | The Google V8 bindings in Google Chrome before 4.1.249.1059 allow attackers to cause a denial of service (memory corruption) via unknown vectors. | no | — | [Chrome 4.1.249.1059 - 2010-04-20](https://chromereleases.googleblog.com/2010/04/stable-update-security-fixes.html) |
| CVE-2010-0646 | [31009](https://issues.chromium.org/issues/31009) | Multiple integer signedness errors in factory.cc in Google V8 before r3560, as used in Google Chrome before 4.0.249.89, allow remote attackers to execute arbitrary code in the Chrome sandbox via crafted use of JavaScript arrays. | no | [dddadf9f7e98](https://chromium.googlesource.com/v8/v8/+/dddadf9f7e98bad3ce54676c733e32c91050b24a) | [Chrome 4.0.249.89 - 2010-02-10](https://chromereleases.googleblog.com/2010/02/stable-channel-update.html) |
| CVE-2010-0645 | [31009](https://issues.chromium.org/issues/31009) | Multiple integer overflows in factory.cc in Google V8 before r3560, as used in Google Chrome before 4.0.249.89, allow remote attackers to execute arbitrary code in the Chrome sandbox via crafted use of JavaScript arrays. | no | [dddadf9f7e98](https://chromium.googlesource.com/v8/v8/+/dddadf9f7e98bad3ce54676c733e32c91050b24a) | [Chrome 4.0.249.89 - 2010-02-10](https://chromereleases.googleblog.com/2010/02/stable-channel-update.html) |
