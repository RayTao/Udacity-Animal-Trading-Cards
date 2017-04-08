# Udacity-Animal-Trading-Cards
use HTML and CSS to create a web match design-prototype.png



1. 下载并解压 [animal-trading-cards_zh.zip](https://github.com/udacity/cn-frontend-development-basic/raw/master/animal-trading-cards_zh.zip)。解压后的文件夹中，你可以找到 `card.html`、`styles.css`、`placeholder.png` 和 `design-prototype.png`。
2. 接下来，打开 `card.html` 并将占位符图片和信息替换为你最喜欢动物的图片和信息。对于图片，你需要使用 `width` 为 300 像素的图片。如果你的图片原始大小更大，你可以在 CSS 中将图片的宽度设置为 300 像素， 但是要知道，你的图片最终可能会压缩或失真。在之后的课程中，我们会讨论如何使用响应式图片来解决这个问题。 而且，不要忘记将图片的 `alt` 属性更改为动物的名称。所以，`alt="name-of-your-animal"` 应替换为动物的实际名称。
3. 添加完你最喜欢的动物的图片和信息后，将正确的 CSS 添加到 `styles.css`， 参考步骤 4 中的样式规则，来创建出和 `design-prototype.png` 一样的动物卡片网页。你将需要修改 `card.html`， 包括 `attributes`， 并使用 `selectors` 来指定你想要使用的元素。而且，确保链接到 `card.html` 中的样式表， 否则你的 CSS 将不会应用到你的网页。
4. CSS 应该应用这些样式，来匹配设计原型：
   - 将动物有趣的事实的文本排成斜体
   - 加粗动物的列表项（例如 `Habitat`）的标记
   - 动物的列表项没有点
   - 围绕动物的名称、图片和信息加边框
   - 围绕动物的信息加边框
   - 动物的名称、图片和信息之间保留一定间距（你将需要使用“[内边距（padding）](https://developer.mozilla.org/zh-CN/docs/Web/CSS/padding)”属性）