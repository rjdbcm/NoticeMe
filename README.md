# NoticeMe

Standardized NOTICE.md for open source developers.

Frequently as open source developers we find ourselves bound by the requirements of a license to attribute or include notice in some form.
This project is an attempt at a standardized way of relaying human friendly and machine readable license attribution and/or notice.

## License for README.md

 <p xmlns:cc="http://creativecommons.org/ns#" xmlns:dct="http://purl.org/dc/terms/"><a property="dct:title" rel="cc:attributionURL" href="https://github.com/rjdbcm/NoticeMe/blob/main/README.md">NoticeMe's Specification and Readme</a> by <a rel="cc:attributionURL dct:creator" property="cc:attributionName" href="https://github.com/rjdbcm">Ross J. Duff MSc</a> is licensed under <a href="http://creativecommons.org/licenses/by-nd/4.0/?ref=chooser-v1" target="_blank" rel="license noopener noreferrer" style="display:inline-block;">Attribution-NoDerivatives 4.0 International
 
This file does not need to be transmitted with NOTICE.md
 
 <img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/cc.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/by.svg?ref=chooser-v1"><img style="height:22px!important;margin-left:3px;vertical-align:text-bottom;" src="https://mirrors.creativecommons.org/presskit/icons/nd.svg?ref=chooser-v1"></a></p>

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
