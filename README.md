# Financial-Dependencies-Environmental-Regulation-Evidence-From-China

The full paper in PDF format can be downloaded from here: [Link](https://github.com/thomaspernet/Financial-Dependencies-Environmental-Regulation-Evidence-From-China/raw/master/Financial_Dependencies__Environmental_Regulation__and_Pollution_Intensity__Evidence_From_China.pdf)

# Data



The project's codes and documentions are available:

- Data preprocessing main dataset
  - [notebook](https://nbviewer.jupyter.org/github/thomaspernet/DataLab-JupyterNotebooks/blob/master/Notebook_dataprocessing/CreditConstraint_SO2_China_preprocessing.ipynb)
  - [Source code](https://github.com/thomaspernet/DataLab-JupyterNotebooks/blob/master/Notebook_dataprocessing/python_programs/Pollution/SBC_pollution.py)
- Data Analysis
  - [notebook](https://nbviewer.jupyter.org/github/thomaspernet/DataLab-JupyterNotebooks/blob/master/Notebook_analysis_lab/Pollution_and_Credit_Constraint/Pollution_and_Credit_Constraint_analysis.ipynb)


Main dataset and TFP dataset are available upon reques, or will soon be available through Binder.

# Introduction

The Global South, and more particularly China, is becoming increasingly responsible for global warming. Consequently, there is a growing awareness that a few important emerging countries such as China and India need to make a swift transition towards a cleaner model of economic growth, which is particularly challenging given the fast increase in a consumption-oriented middle class ([OECD report, Development Matters 2019](https://oecd-development-matters.org/2019/06/20/the-global-souths-contribution-to-the-climate-crisis-and-its-potential-solutions/) However, this challenge can also bring many opportunities. According to the [International Energy Agency’s World Energy Investment 2019 report](https://www.iea.org/wei2019/), "global power investment is shifting towards emerging and developing countries [with] remarkable investment in renewable … In most regions, low-carbon sources were the largest part of generation spending … [and] in India, total renewable power investment topped fossil fuel-based power for the third year in a row."

Concern about environmental issues is also growing dramatically in China, which stands out because of its environmental disasters and poor air quality.

China has experienced numerous disasters, which impact the health of the population and nourish political discontent. In addition, China is a major global air polluter and has had a significant increase in the emission of sulfur dioxide (SO2) since its entry into the WTO in 2001, which reached a peak in 2006. Interestingly, this trend has since been declining (see figure (see figure1). This reduction coincides with the introduction of stringent environmental measures by the central government.

Previous studies point to the improvement of environmental metrics by reallocating production away from polluting sectors. However, except for Andersen 2015, 2017 and Earnhart 2012, little research has paid attention to the relationship between the financial system and environmental issues. This paper aims to make a contribution to this area of research by investigating the effectiveness of credit reallocation away from polluting projects in the context of environmental policy change, or how a bank’s involvement in a firm's financing may be in line with environmental policies pursued by the Chinese central government. Banks indeed have a central role to play in promoting sustainable development—they finance cleaner projects and help firms to adopt cleaner technology.

There is a large literature of firms' environmental performance, in both developed (e.g. Gray1996, Cole 2005, Shadbegian 2005, Earnhart 2012) and developing countries (e.g. Earnhart 2006, Cole 2008). In this paper we focus on China because it is an ideal candidate to study the link between financial dependency and environmental performance. Although it is relatively inefficient (Boyreau-Debray 2003, Dollar 2007), the Chinese financial market went through rapid reform over a short time span to cope with the transition to a market-driven economy (Jarreau 2014). Banking assets form the majority of loans (i.e., about 85\%), and are dominated by the four state-owned commercial banks (Allen 2009). The entry of China to the WTO in 2001 triggered a rapid economic growth and environmental degradation, which was caused by mismanagement of resources and mass industrialization. However, China was not impacted equally, providing considerable spatial variations across coastal and inner-land provinces, and giving our estimation strategy enough variability to identify the link between financial performance and environmental regulations. 

In this paper, we use the most extensive environmental statistics available in China. This dataset is collected and maintained by the Ministry of Environmental Protection (MEP) and it gathers information about the emission of major pollutants such as sulfur dioxide, which is our variable of interest, wastewater, chemical oxygen demand, and industrial dust, and it covers all industrial sectors. To our knowledge, only a few studies have used this thin level of pollution emissions in China. We are able to track most of the industrial emissions of SO2 during six consecutive years (2002–2007) at the level of industries, provinces, and cities. 

The 11th five-year plan (FYP) was launched in 2006. It issued a set of quantitative measures of pollution reduction targets at the national and local levels, which were spread unequally across China, with some provinces being required to exert higher efforts while others were required to make lower efforts. The sectoral financial dependency captures the extent to which an industry needs to rely on external financing.

We conduct a difference-in-difference-in-difference (DDD) estimate to evaluate the effect of the credit reallocation that was induced by the shift of policy emphasis towards environmental concerns after 2006. Specifically, we compare the before and after variations of SO2 emissions by dividing the sample into pre- and post-treatment periods. We interact with a time dummy that is equal to one after 2006 with the pollution reduction target and the sectoral financial dependency. The advantage of the triple difference is the possibility to include the full fixed effects of city-industry, city-year, and industry-year. The triple pairs of fixed effects can alleviate the potential omitted variables from both the city and industry levels across time. Thanks to market incentives and policy orientation, China’s banks are now shifting the flow of capital into projects that are in line with the government's environmental objective of SO2 emission reduction.

Our results are twofold. First, we find strong evidence that financially more dependent sectors with higher reduction targets emit less SO2, which confirms our hypothesis of a credit shift in favor of sustainable finance. Our estimates show that an increase of the regulation stringency by 1500 tons of SO2 above the cities means reduces the emission of SO2 by 3.54%. It has also been shown by research for the European Commission that the external damage cost of one ton of SO2 is valued at $7228. Therefore, our computation shows that an average city can save up to $29 million per year.

We also confirm that our results are not sensitive to outliers and are not driven by the pre-trend effect. We also find that private *versus* state-owned enterprises (SOE), or domestic *versus* foreign enterprises, do not react with the same intensity to the environmental regulations.

Our results suggest that the government should act in favor of stringent and coordinated environmental policies. As a result, market mechanisms will allocate efficiently capital for sustainable finance.

Second, we test whether our results are in line with the growing literature on the pollution haven hypothesis (PHH). Specifically, we construct a variable to capture the reallocation effect. We then divide each city in our sample dataset based on whether the environmental effort is large enough to provide an incentive for a firm to leave. Our results suggest that a stronger deterrent effect of environmental regulation leads firms to seek funding in less restricted provinces, confirming the pollution haven hypothesis (PVH). Our results are in line with previous works in the area (Hering 2014, Chen 2018, Shi 2018)

![fig 1](https://github.com/thomaspernet/Financial-Dependencies-Environmental-Regulation-Evidence-From-China/blob/master/Paper/images/fig_1.jpg)
