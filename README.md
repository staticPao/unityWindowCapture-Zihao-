# Australia_COVID-19_AnalysisPractice
本实践的数据来自（https://covidlive.com.au/)  旨在分析和可视化维多利亚州、新南威尔士州和西澳大利亚州三个州的 COVID-19 病例数据和相关信息（具体包括病例的发展和分布、疫苗接种情况及其与病例的关系、住院情况及其与病例的关系）分析结果有助于解释上述三个或更多州的 COVID-19 病例分布

其中的**download.R**用于从网站中爬取数据，如果需要获取更多州的信息，直接更改或增加链接末端州的缩写即可

**analysis.R**用于将爬到的数据数据进行分析和可视化

**app.R**基于shiny包实现可交互的可视化图表（具体包括控制时间区间和周数）

