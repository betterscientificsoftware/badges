# Exascale Computing Project Badges

[![ECP](ecp.svg)](https://exascaleproject.org)
[![Scale eflops](scale-eflops.svg)]()


These badges are provided by the [IDEAS-ECP](https://ideas-productivity.org) group.
They are free-to-use by members of the ECP community.

Some Examples Mark put together using [shields.io](https://shields.io)

* Using Shields basic mode
  * ![](https://img.shields.io/badge/scale-eflops-brightgreen.svg)
  * This is simpler than creating/storing our own svg as example above does
* Using Shields json endpoint...which refers to some json file somewhere.
  * ![Custom badge](https://img.shields.io/badge/endpoint.svg?style=plastic&url=https%3A%2F%2Fraw.githubusercontent.com%2Fexascaleproject%2Fbadges%2Fmaster%2Fllnl_logo_endpoint.json)
  * This also allows for the badges to be *dynamic* in that changing the underlying JSON endpoint file then results in changing the badge.
  * However, these tiny images are generated and cached on shields.io servers for a minimum of 300 seconds and so the soonest you may observe changes to an already existing rendered badge is after 300 seconds.
  * You can adjust the cache *life* of a badge on shields.io but the minimum is 300 seconds.
* Using custom svg base64 encoded into the shields.io query string
  * ![](https://img.shields.io/badge/play-user-blue.svg?logo=data:image/svg%2bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZlcnNpb249IjEiIHdpZHRoPSI2MDAiIGhlaWdodD0iNjAwIiB2aWV3Qm94PSIwIDAgNDAgNDAiPjxwYXRoIGZpbGw9IiNGMDAiIGQ9Ik0zNS45MiwwLjAxdjE3LjUzSDE4Ljk1VjAuMDFIMzUuOTJ6IE0xNS44OCwyMS44MmMtMS4xMi0wLjA3LTEuNzItMC43OC0xLjc5LTIuMVYwLjAxaC0wLjc2djE5LjczYzAuMDksMS43MiwxLDIuNzUsMi41MywyLjg0aDE1LjI4bC00LjgzLDVsLTExLjc5LDBjLTMuMDQtMC4zNi02LjIyLTIuOTMtNi4xNC02Ljk4VjAuMDFINy42VjIwLjZjLTAuMDksNC40OSwzLjQ1LDcuMzQsNi44Niw3Ljc1aDExLjA5bC00LjU5LDQuNzVoLTYuNjhDOS43MSwzMi45MywzLjE5LDI5LjQ0LDIuOTksMjEuMTNWMC4wMUgwLjA1djM3LjNoMzUuODdWMTcuNjJsLTQuMDUsNC4xOUwxNS44OCwyMS44MnoiLz48L3N2Zz4=)
* Using popout style (which makes the logo larger than the badge size limits
  * ![](https://img.shields.io/badge/play-user-blue.svg?style=popout&logo=data:image/svg%2bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZlcnNpb249IjEiIHdpZHRoPSI2MDAiIGhlaWdodD0iNjAwIiB2aWV3Qm94PSIwIDAgNDAgNDAiPjxwYXRoIGQ9Ik0zNS45MiwwLjAxdjE3LjUzSDE4Ljk1VjAuMDFIMzUuOTJ6IE0xNS44OCwyMS44MmMtMS4xMi0wLjA3LTEuNzItMC43OC0xLjc5LTIuMVYwLjAxaC0wLjc2djE5LjczYzAuMDksMS43MiwxLDIuNzUsMi41MywyLjg0aDE1LjI4bC00LjgzLDVsLTExLjc5LDBjLTMuMDQtMC4zNi02LjIyLTIuOTMtNi4xNC02Ljk4VjAuMDFINy42VjIwLjZjLTAuMDksNC40OSwzLjQ1LDcuMzQsNi44Niw3Ljc1aDExLjA5bC00LjU5LDQuNzVoLTYuNjhDOS43MSwzMi45MywzLjE5LDI5LjQ0LDIuOTksMjEuMTNWMC4wMUgwLjA1djM3LjNoMzUuODdWMTcuNjJsLTQuMDUsNC4xOUwxNS44OCwyMS44MnoiLz48L3N2Zz4=)
* Using PNG instead of SVG
  * ![](https://img.shields.io/badge/play-user-blue.svg?logo=data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAABAAAAAQCAMAAAAoLQ9TAAAABGdBTUEAALGPC/xhBQAAAAFzUkdCAK7OHOkAAAILaVRYdFhNTDpjb20uYWRvYmUueG1wAAAAAAA8eDp4bXBtZXRhIHhtbG5zOng9ImFkb2JlOm5zOm1ldGEvIiB4OnhtcHRrPSJYTVAgQ29yZSA1LjQuMCI+CiAgIDxyZGY6UkRGIHhtbG5zOnJkZj0iaHR0cDovL3d3dy53My5vcmcvMTk5OS8wMi8yMi1yZGYtc3ludGF4LW5zIyI+CiAgICAgIDxyZGY6RGVzY3JpcHRpb24gcmRmOmFib3V0PSIiCiAgICAgICAgICAgIHhtbG5zOnRpZmY9Imh0dHA6Ly9ucy5hZG9iZS5jb20vdGlmZi8xLjAvIj4KICAgICAgICAgPHRpZmY6UmVzb2x1dGlvblVuaXQ+MjwvdGlmZjpSZXNvbHV0aW9uVW5pdD4KICAgICAgICAgPHRpZmY6Q29tcHJlc3Npb24+MTwvdGlmZjpDb21wcmVzc2lvbj4KICAgICAgICAgPHRpZmY6T3JpZW50YXRpb24+MTwvdGlmZjpPcmllbnRhdGlvbj4KICAgICAgICAgPHRpZmY6UGhvdG9tZXRyaWNJbnRlcnByZXRhdGlvbj4yPC90aWZmOlBob3RvbWV0cmljSW50ZXJwcmV0YXRpb24+CiAgICAgIDwvcmRmOkRlc2NyaXB0aW9uPgogICA8L3JkZjpSREY+CjwveDp4bXBtZXRhPgoPRSqTAAAACXBIWXMAAAsTAAALEwEAmpwYAAAAM1BMVEX////W1tZlZWXOzs5/f3+dnZ2IiIj9/f0AAAB0dXWkpKTp6ekYGBjJycn19fUkIiKTk5PDMBiaAAAAc0lEQVQY052OWw5DIQhEEXkMqOnd/2or3rZp0r9OAnFOYJA8oBBDJ6ejf0HIL1jkRx/QiL4zBNlW73018v2erLg192AiGZeKiEXUYgPnA7xB2KhTbrDkiVnzdYUGg1XVdJSvGlZ5fPtDvGXl+fuv/mrHPwGnmQUCkTiwFAAAAABJRU5ErkJggg==)
  * note: uuencoded PNG requires a lot of chars and may exceed URL length limits for some browsers
  * I used [pngquant](https://pngquant.org) tool to minify the PNG used in this example
