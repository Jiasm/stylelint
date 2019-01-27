# 处理器

处理器是一些社区包，使 stylelint 能够从非样式表文件中提取样式。

*以下处理器仅用于命令行界面和 Node.js 应用程序接口，而不能用于 PostCSS 插件。*（PostCSS 插件将忽略它们。）

-   [stylelint-processor-arbitrary-tags](https://github.com/mapbox/stylelint-processor-arbitrary-tags): 检查用户指定的标签中的样式。

stylelint 已经内置了对许多常用的非样式表文件的支持。您可能不再需要使用以下处理器：

-   [stylelint-processor-glamorous](https://github.com/zabute/stylelint-processor-glamorous): 用于检查 [glamorous](https://github.com/paypal/glamorous) 以及基于对象字面量的 CSS-in-JS 方案中的样式。
-   [stylelint-processor-markdown](https://github.com/mapbox/stylelint-processor-markdown): 用于检查 Markdown 的[受控代码块](https://help.github.com/articles/creating-and-highlighting-code-blocks/)中的样式。
-   [stylelint-processor-styled-components](https://github.com/styled-components/stylelint-processor-styled-components): 用于检查 [styled-components](https://styled-components.com) 以及基于模板字面量的 CSS-in-JS 方案中的样式。
