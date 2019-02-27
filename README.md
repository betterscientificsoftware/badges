# Exascale Computing Project Badges

[![ECP](ecp.svg)](https://exascaleproject.org)
[![Scale eflops](scale-eflops.svg)]()


These badges are provided by the [IDEAS-ECP](https://ideas-productivity.org) group.
They are free-to-use by members of the ECP community.

Some Examples Mark put together using [shields.io](https://shields.io). If you click on the badges, it will take you to a page showing the badge zoomed in.

* Using Shields basic mode
  * ![](https://img.shields.io/badge/scale-eflops-brightgreen.svg)
  * This is simpler than creating/storing our own svg as example above does
* Using Shields JSON endpoint mode
  * The JSON files referenced in these URLs are the ones in this repo.
  * ![Custom badge](https://img.shields.io/badge/endpoint.svg?style=plastic&url=https%3A%2F%2Fraw.githubusercontent.com%2Fexascaleproject%2Fbadges%2Fmaster%2Fllnl_logo_endpoint.json)
  * ![Custom badge](https://img.shields.io/badge/endpoint.svg?style=popout&url=https%3A%2F%2Fraw.githubusercontent.com%2Fexascaleproject%2Fbadges%2Fmaster%2Fornl_logo_endpoint.json)
    * In above, icon intentionally extends outside of badge using *popout* style.
  * ![Custom badge](https://img.shields.io/badge/endpoint.svg?style=popout-square&url=https%3A%2F%2Fraw.githubusercontent.com%2Fexascaleproject%2Fbadges%2Fmaster%2Fanl_logo_endpoint.json)
    * In above, the svg needs to be scaled a tad larger (easily done) because here it is also using *popout* style but does not extend outside of badge. I am also using the *square* style which is intionally a tad larger than other badges.
    * I wound up fiddling around a bit too much trying to adjust scaling and offset of the svg strings used here.
  * This also allows for the badges to be *dynamic* in that changing the underlying JSON endpoint file then results in changing the badge.
  * However, these tiny images are generated and cached on shields.io servers for a minimum of 300 seconds and so the soonest you may observe changes to an already existing rendered badge is after 300 seconds.
  * You can adjust the cache *life* of a badge on shields.io but the minimum is 300 seconds.
  * ![Custom badge](https://img.shields.io/endpoint.svg?style=popout&url=https%3A%2F%2Fraw.githubusercontent.com%2Fexascaleproject%2Fbadges%2Fmaster%2Fci4ecp_logo_endpoint.json)
    * The above is a draft of logo for the CI4ECP work
* Using custom logo (svg or png) base64 encoded directly into the shields.io query string
  * ![](https://img.shields.io/badge/play-user-blue.svg?logo=data:image/svg%2bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZlcnNpb249IjEiIHdpZHRoPSI2MDAiIGhlaWdodD0iNjAwIiB2aWV3Qm94PSIwIDAgNDAgNDAiPjxwYXRoIGZpbGw9IiNGMDAiIGQ9Ik0zNS45MiwwLjAxdjE3LjUzSDE4Ljk1VjAuMDFIMzUuOTJ6IE0xNS44OCwyMS44MmMtMS4xMi0wLjA3LTEuNzItMC43OC0xLjc5LTIuMVYwLjAxaC0wLjc2djE5LjczYzAuMDksMS43MiwxLDIuNzUsMi41MywyLjg0aDE1LjI4bC00LjgzLDVsLTExLjc5LDBjLTMuMDQtMC4zNi02LjIyLTIuOTMtNi4xNC02Ljk4VjAuMDFINy42VjIwLjZjLTAuMDksNC40OSwzLjQ1LDcuMzQsNi44Niw3Ljc1aDExLjA5bC00LjU5LDQuNzVoLTYuNjhDOS43MSwzMi45MywzLjE5LDI5LjQ0LDIuOTksMjEuMTNWMC4wMUgwLjA1djM3LjNoMzUuODdWMTcuNjJsLTQuMDUsNC4xOUwxNS44OCwyMS44MnoiLz48L3N2Zz4=)
* Using popout style with
  * ![](https://img.shields.io/badge/play-user-blue.svg?style=popout&logo=data:image/svg%2bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZlcnNpb249IjEiIHdpZHRoPSI2MDAiIGhlaWdodD0iNjAwIiB2aWV3Qm94PSIwIDAgNDAgNDAiPjxwYXRoIGQ9Ik0zNS45MiwwLjAxdjE3LjUzSDE4Ljk1VjAuMDFIMzUuOTJ6IE0xNS44OCwyMS44MmMtMS4xMi0wLjA3LTEuNzItMC43OC0xLjc5LTIuMVYwLjAxaC0wLjc2djE5LjczYzAuMDksMS43MiwxLDIuNzUsMi41MywyLjg0aDE1LjI4bC00LjgzLDVsLTExLjc5LDBjLTMuMDQtMC4zNi02LjIyLTIuOTMtNi4xNC02Ljk4VjAuMDFINy42VjIwLjZjLTAuMDksNC40OSwzLjQ1LDcuMzQsNi44Niw3Ljc1aDExLjA5bC00LjU5LDQuNzVoLTYuNjhDOS43MSwzMi45MywzLjE5LDI5LjQ0LDIuOTksMjEuMTNWMC4wMUgwLjA1djM3LjNoMzUuODdWMTcuNjJsLTQuMDUsNC4xOUwxNS44OCwyMS44MnoiLz48L3N2Zz4=)
  * Using better LLNL logo svg and logo color encoded into query string
    * ![](https://img.shields.io/badge/play-user-blue.svg?style=popout&logoColor=0033a1&logo=data:image/svg%2bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCA1NyA1NyI+PHBhdGggZD0iTTYwLjUyLDMzLjc0bC02Ljc2LDdIMjYuNUEyLjgzLDIuODMsMCwwLDEsMjMuNjEsMzhWMy42OGg4LjI4djI4LjZINjEuN1oiIHRyYW5zZm9ybT0idHJhbnNsYXRlKC00LjM0IC0zLjY4KSIvPjxwYXRoIGQ9Ik0xMy44NCwzLjY4VjM4LjgzQTExLjYzLDExLjYzLDAsMCwwLDI0LjE4LDUwLjU3SDQ0LjI1bDcuOTMtOC4yMUgyNi40NUE0LjQ4LDQuNDgsMCwwLDEsMjIsMzguMDhWMy42OFoiIHRyYW5zZm9ybT0idHJhbnNsYXRlKC00LjM0IC0zLjY4KSIvPjxwYXRoIGQ9Ik00LjM0LDMuNjh2MzZjLjM0LDE0LjE4LDExLjQ3LDIwLjE1LDE5LjI3LDIwLjQySDM1bDcuNjctNy45NEgyNC4wOEExMy4yNiwxMy4yNiwwLDAsMSwxMi4yMSwzOC44MVYzLjY4WiIgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoLTQuMzQgLTMuNjgpIi8+PC9zdmc+Cg==)
  *  Popout allows custom logos to extend outside the badge edges as in ![](https://img.shields.io/static/v1.svg?label=build&message=passing&color=brightgreen&style=popout&logo=appveyor)
* Using PNG instead of SVG
  * ![](https://img.shields.io/badge/play-user-blue.svg?logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAQCAMAAAAoLQ9TAAAABGdBTUEAALGPC/xhBQAAAAFzUkdCAK7OHOkAAAILaVRYdFhNTDpjb20uYWRvYmUueG1wAAAAAAA8eDp4bXBtZXRhIHhtbG5zOng9ImFkb2JlOm5zOm1ldGEvIiB4OnhtcHRrPSJYTVAgQ29yZSA1LjQuMCI+CiAgIDxyZGY6UkRGIHhtbG5zOnJkZj0iaHR0cDovL3d3dy53My5vcmcvMTk5OS8wMi8yMi1yZGYtc3ludGF4LW5zIyI+CiAgICAgIDxyZGY6RGVzY3JpcHRpb24gcmRmOmFib3V0PSIiCiAgICAgICAgICAgIHhtbG5zOnRpZmY9Imh0dHA6Ly9ucy5hZG9iZS5jb20vdGlmZi8xLjAvIj4KICAgICAgICAgPHRpZmY6UmVzb2x1dGlvblVuaXQ+MjwvdGlmZjpSZXNvbHV0aW9uVW5pdD4KICAgICAgICAgPHRpZmY6Q29tcHJlc3Npb24+MTwvdGlmZjpDb21wcmVzc2lvbj4KICAgICAgICAgPHRpZmY6T3JpZW50YXRpb24+MTwvdGlmZjpPcmllbnRhdGlvbj4KICAgICAgICAgPHRpZmY6UGhvdG9tZXRyaWNJbnRlcnByZXRhdGlvbj4yPC90aWZmOlBob3RvbWV0cmljSW50ZXJwcmV0YXRpb24+CiAgICAgIDwvcmRmOkRlc2NyaXB0aW9uPgogICA8L3JkZjpSREY+CjwveDp4bXBtZXRhPgoPRSqTAAAACXBIWXMAAAsTAAALEwEAmpwYAAAAM1BMVEX////W1tZlZWXOzs5/f3+dnZ2IiIj9/f0AAAB0dXWkpKTp6ekYGBjJycn19fUkIiKTk5PDMBiaAAAAc0lEQVQY052OWw5DIQhEEXkMqOnd/2or3rZp0r9OAnFOYJA8oBBDJ6ejf0HIL1jkRx/QiL4zBNlW73018v2erLg192AiGZeKiEXUYgPnA7xB2KhTbrDkiVnzdYUGg1XVdJSvGlZ5fPtDvGXl+fuv/mrHPwGnmQUCkTiwFAAAAABJRU5ErkJggg==)
  * note: uuencoded PNG requires a lot of chars and may exceed URL length limits for some browsers
  * I used [pngquant](https://pngquant.org) tool to minify the PNG used in this example
