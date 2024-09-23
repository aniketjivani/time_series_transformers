Explore various transformer-based architectures and their performance on background solar wind data?

Univariate:

- LagLLAMA: https://arxiv.org/abs/2310.08278

- TimeGPT (Nixtla): https://github.com/Nixtla/nixtla (can handle multiple series concurrently, but forecasts are still univariate?)

Multivariate:

- Uni2TS (Salesforce AI Research): https://arxiv.org/abs/2402.02592

- iTransformer (Tsinghua): GitHub: https://github.com/thuml/iTransformer and https://github.com/lucidrains/iTransformer . Paper: https://arxiv.org/abs/2310.06625 (little difficult to read, but definitely a very popular architecture)

Dataset sources (iTransformer):

- Weather - https://www.bgc-jena.mpg.de/wetter/

- Solar - https://www.nrel.gov/grid/solar-power-data.html