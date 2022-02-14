# 简介



<img src="https://www.tradingview.com/pine-script-docs/en/v4/_images/Pine_Script_logo_text.png" alt="Pine Script logo" style="zoom: 40%;float:right" />

TradingView设计了自己的脚本语言，称为 Pine脚本。它允许用户创建自定义指标并在TradingView的服务器上运行它们。Pine被设计为一种轻量级语言，专注于开发指标和策略这种特定任务。TradingView的大多数内置指标都是用Pine编写的。我们的最终目标是让广泛的用户对Pine更易接受并且容易理解。

Pine是基于云的，因此本质上不同于客户端编程语言。虽然我们不会将Pine变成具有高级编程功能的成熟语言，具有构建非常复杂程序的能力，但不断改进Pine是我们的重中之重，我们很高兴考虑对新功能的任何要求。

因为每个脚本都使用云中的计算资源，所以我们必须施加限制，以便在用户之间公平地共享这些资源。我们努力施加尽可能少的限制，同时执行尽可能多的需求。我们必须确保平台保持平稳运行，这样没有人会受到过度消耗资源的脚本的负面影响。施加的限制适用于诸如来自添加标的的数据大小，执行时间，内存使用量和脚本大小等元素。此外，我们使Pine语法和语义保持简单，以便它可以有效地处理常见任务。

我们将继续改善Pine的文档和支持，以确保任何人都可以学习和使用Pine，因为这有助于发展Pine开发社区，并为TradingView用户提供更强大和有用的工具。