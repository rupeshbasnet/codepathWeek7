# Project 7 - WordPress Pentesting

Time spent: **4** hours spent in total

> Objective: Find, analyze, recreate, and document **five vulnerabilities** affecting an old version of WordPress

## Pentesting Report

1. (Required) Vulnerability Name or ID
  - [X] Summary: 
    - Vulnerability types: Input Sanitization Vulnerbility (XSS Vulnerbility)
    - Tested in version: Version less than or equal to 4.2
    - Fixed in version: >= 4.2.3
  - [X] GIF Walkthrough:
  ![img](https://i.imgur.com/gFhAACd.gif)
  - [X] Steps to recreate: 1. Create a new Post 2. On the title of the post create "a" tag with the event handler and insert the script inside the event handler.
  - [X] Affected source code: 
    - [Link 1](https://core.trac.wordpress.org/browser/tags/4.2/src/wp-includes/default-widgets.php)
2. (Required) Vulnerability Name or ID
  - [X] Summary:  
    - Vulnerability types: Input Sanitization Vulnerbility (XSS Vulnerbility)
    - Tested in version: Version <= 4.2
    - Fixed in version: >= 4.2.3
  - [X] GIF Walkthrough:
  ![img](https://i.imgur.com/WXIouKK.gif)
  - [X] Steps to recreate: 1. Edit a page 2. On the text description add an Iframe XSS script. 
  - [X] Affected source code:
    - [Link 1](https://core.trac.wordpress.org/browser/tags/4.2/src/wp-includes/shortcodes.php)
3. (Required) Vulnerability Name or ID
  - [X] Summary: 
    - Vulnerability types:Input Sanitization Vulnerbility (XSS Vulnerbility)
    - Tested in version:Version <= 4.2
    - Fixed in version: >= 4.2.3
  - [X] GIF Walkthrough: ![img](https://i.imgur.com/2jT2ySN.gif)
  - [X] Steps to recreate: 1. Open a post 2. Write a new comment. 3. On the new comment, insert an Img tag XSS script.
  - [X] Affected source code:
    - [Link 1](https://www.cvedetails.com/cve/CVE-2015-3438/)

## Assets

List any additional assets, such as scripts or files

## Resources

- [WordPress Source Browser](https://core.trac.wordpress.org/browser/)
- [WordPress Developer Reference](https://developer.wordpress.org/reference/)

GIFs created with [LiceCap](http://www.cockos.com/licecap/).

## Notes

Describe any challenges encountered while doing the work

## License

    Copyright [yyyy] [name of copyright owner]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
