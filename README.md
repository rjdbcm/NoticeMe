# NoticeMe

Standardized NOTICE.md for open source developers.

Frequently as open source developers we find ourselves bound by the requirements of a license to attribute or include notice in some form.
This project is an attempt at a standardized way of relaying human friendly and machine readable license attribution and/or notice.

## Normative References

The following contains normative references to the [CommonMark v0.30](https://spec.commonmark.org/0.30) specification.

## Using NoticeMe

The recommended way of using NoticeMe as of v2.0.1 is to include applicable license identifiers in `NOTICE.md` as second-level ATX headings.
Then attribution(s) at the third-level headings with the requisite text at the level of the applicable attribution.
e.g. 

```
## SPDX-License-Identifier: MIT
### Attribution: John A. Smith

Permission is hereby granted,
...
The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.
...
```
