# Why cannot you set up Xdebug?

Most users experience difficulties with setting up [Xdebug](https://xdebug.org/) in their development environments. The problem has deteriorated due to several reasons:

- Insufficient understanding of xdebug work
- An overload of ambiguous and inaccurate google-answers
- No out-of-the-box solution to run "in one click"

As long as the last two reasons are hard to affect, the focus of the article is decreasing impact of the first reason. So the goal is to explain how Xdebug does work under the hood, how IDE does work with Xdebug, and how the browser side has to work. The narrative format will help you systematize knowledge in an orderly manner. As a result, the acquired knowledge will reduce efforts on setting Xdebug up in an unfamiliar environment.

In addition, you will gain insights into the following related questions: what is DBGp Proxy, why you should not use Xdebug Cloud and how to set up Xdebug in nonstandard environments (like SPA application).

The document is presented in two languages:

- [English](./xdebug_en.md)
- ~~[Русский](./xdebug_ru.md)~~

### TODO List

- WSL2 environment