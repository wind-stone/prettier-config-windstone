# prettier-config-windstone

Wind Stone's Prettier config

| 配置项                    | 默认值      | 取值        | 意义                                                         |
| ------------------------- | ----------- | ----------- | ------------------------------------------------------------ |
| printWidth                | 80          | 120         | 行宽                                                         |
| tabWidth                  | 2           | 4           | 指定每个缩进的空格数量                                       |
| useTabs                   | false       | false       | 行的缩进是否使用 Tab 而不是空格                              |
| semi                      | true        | true        | 语句行尾是否添加分号                                         |
| singleQuote               | false       | true        | 字符串是否使用单引号而不是双引号                             |
| quoteProps                | "as-needed" | "as-needed" | 对象的属性是否要加引号                                       |
| jsxSingleQuote            | false       | false       | JSX 里是否使用单引号而不是双引号                             |
| trailingComma             | "none"      | "es5"       | 多行时任何可能的地方是否添加尾逗号                           |
| bracketSpacing            | true        | true        | 对象字面量的大括号内部是否添加空格                           |
| jsxBracketSameLine        | true        | false       | 是否将`>`放置在多行 JSX 元素最后一行的结尾，而不是放在下一行 |
| arrowParens               | "avoid"     | "avoid"     | 箭头函数只有一个参数时，参数是否使用圆括号                   |
| rangeStart                | 0           | 0           | 被格式化文件的行起点                                         |
| rangeEnd                  | Infinity    | Infinity    | 被格式化文件的行终点                                         |
| parser                    | -           | -           | 指定使用的解析器                                             |
| filepath                  | -           | -           | 指定使用哪个文件来指明使用哪个解析器                         |
| requirePragma             | false       | false       | 是否在文件顶部包含`@prettier`或`@format`的注释时才格式化     |
| insertPragma              | false       | false       | 是否在文件顶部添加`@format`标记来指明该文件已经被格式化      |
| proseWrap                 | "preserve"  | "preserve"  | 指定如何处理 Markdown 文本的换行                             |
| htmlWhitespaceSensitivity | "css"       | "strict"    | 指定如何 HTML 文件里的全局空白敏感的行为                     |
| endOfLine                 | "auto"      | "lf"        | 采用哪一种行尾换行符                                         |
