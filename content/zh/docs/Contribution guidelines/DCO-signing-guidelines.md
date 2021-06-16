---
title: "DCO签署指南"
linkTitle: "DCO签署指南"
weight: 10
---

### DCO签署流程
Fufile采用对社区更友好的DCO贡献者许可协议。

DCO 是 Developer Certificate of Origin 的缩写，由 Linux Foundation 于 2004 年制定。
```
Developer Certificate of Origin
Version 1.1

Copyright (C) 2004, 2006 The Linux Foundation and its contributors.
1 Letterman Drive
Suite D4700
San Francisco, CA, 94129

Everyone is permitted to copy and distribute verbatim copies of this
license document, but changing it is not allowed.


Developer's Certificate of Origin 1.1

By making a contribution to this project, I certify that:

(a) The contribution was created in whole or in part by me and I
    have the right to submit it under the open source license
    indicated in the file; or

(b) The contribution is based upon previous work that, to the best
    of my knowledge, is covered under an appropriate open source
    license and I have the right under that license to submit that
    work with modifications, whether created in whole or in part
    by me, under the same open source license (unless I am
    permitted to submit under a different license), as indicated
    in the file; or

(c) The contribution was provided directly to me by some other
    person who certified (a), (b) or (c) and I have not modified
    it.

(d) I understand and agree that this project and the contribution
    are public and that a record of the contribution (including all
    personal information I submit with it, including my sign-off) is
    maintained indefinitely and may be redistributed consistent with
    this project or the open source license(s) involved.
```
在每次提交贡献前，若您同意DCO协议，需要将`Signed-off-by`添加到提交的信息中。
```
This is my commit message

Signed-off-by: Random J Developer <random@developer.example.org>
```
Git集成了DCO，您可以方便的通过Git命令将`Signed-off-by`添加到您的提交信息中。
```
git commit -s -m 'This is my commit message'
```