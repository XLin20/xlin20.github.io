# Data Scientist

## Professional Summary 			       		
- Data Scientist with 5+ years of experience applying AI/ML techniques in Earth, Environmental, and Energy systems. Expertise in predictive modeling, data-driven decision-making, and optimization. Strong background in cloud computing, big data processing, automated ETL pipelines, feature engineering, model training and deployment in high-performance computing (HPC) environments. Adept at cross-functional collaboration, translating complex insights into actionable outcomes

## Education 			       		
- M.S., Statistics	| University of Idaho, Moscow, ID, 2016-2018	 			        		
- B.S., Material Engineering | South China University of Technology, China, 2007-2011

## Technical Skills 
- **Machine Learning Techniques**: Supervised and unsupervised learning, Deep Learning (DNN, CNN), and Large Language Models (LLMs).
- **Data Science**: A/B tests, Data mining, Feature Engineering, Data Visualization , Uncertainty Quantification
- **Programming Languages**: Python (scikit-learn, keras, pandas, tensorflow, pytorch, etc.); R (dplyr, ggplot2, caret, cluster, forecast, shiny, etc.), SQL, SAS
- **Computing Environments**: Linux, HPC, Cloud Platforms (AWS, GCP)
- **Certification**: Generative AI with Large Language Models – Coursera (2025)

## Work Experience 
**Data Scientist @ Pacific Northwest National Laboratory (PNNL), Richland, WA (_September 2020 - December 2024_)**
- Developed an automated ML pipeline (i.e., data collection, processing, model trainging) for energy load forecasting under extreme weather scenarios (e.g., heatwave, drought) in the Western U.S. using historical and climate modeling weather data.
- Initiated the development of a high-resolution (i.e.,1 km) AI-ready benchmark data product (2001–2020) on extreme weather events (e.g., fires, heatwaves, and droughts) across the Western U.S.
- Developed an ML-based soil moisture data fusion framework for CONUS (2001–2020) by integrating terabytes of data from over 20 diverse sources (e.g., remote sensing and land surface models etc.).
- Conducted study on the remote impact of Western U.S. wildfires on Central U.S. hails using ML models (Random Forest, XGBoost) and identifying key weather and fire factors with >90% accuracy.
- Identified key factors influencing extreme precipitation across the U.S. using ML methods (i.e., RF, XGBoost, NN), achieving R² > 0.95 for intensity model and >90% accuracy for frequency model.

**Research Associate @ Pacific Northwest National Laboratory (PNNL), Richland, WA (_August 2018 - September 2020_)**
- Built regression models to approximate mixed integer programming (MIP) solutions in Security Constrained Unit Commitment (SCUC) problems, achieving ~78% reduction in discrepancies with linear programming relaxation (LPR).
- Developed classification models to predict generator startup/shutdown probabilities in power system operations, reducing binary decision space  (i.e., commitment status) by 90%.
- Designed automated data processing pipelines for the WHONDRS data package and developed an interactive GUI using R shiny, enabling real-time data visualization for scientists and researchers.

## Projects |
### Machine Learning Analysis of Impact of Western US Fires on Central US Hailstorms 
[Publication](https://doi.org/10.1007/s00376-024-3198-7)

RF and XGB models are developed using **Python** to establish connections between WUS fires and large hail occurrence in the CUS. The built ML models can make accurate predictions for large hail occurrence in several central US states. This paper is a contribution to the special issue on AI Applications in Atmospheric and Oceanic Science: Pioneering the Future.

![Wildfires Remote Impact](/assets/img/WF_remote_map.png |width=100)

### An Inventory of AI-ready Benchmark Data for US Fires, Heatwaves, and Droughts.
[Publication](https://doi.org/10.25584/2004956)

Developed a comprehensive benchmark data inventory of extreme weather events including fires, heatwaves, and droughts (2001-2020) over the CONUS(0.5°×0.5°), and the Pacific Northwest region (1km × 1km), together with the co-located and relevant meteorological variables. This study can contribute significantly to the advancement of extreme weather research, aiding researchers, policymakers, and practitioners in developing improved preparedness and response strategies to protect communities and ecosystems from the adverse impacts of extreme weather events.

![Data Inventory Flowchart](/assets/img/LDRD_project_flowcharts_eplots_1.png |width=100)

### Machine learning of key variables impacting extreme precipitation in various regions of the contiguous United States
[Publication](https://doi.org/10.1029/2022MS003334)

Employed ensemble machine learning (ML) methods, namely random forest (RF), eXtreme Gradient Boosting (XGB), and artificial neural networks (ANN), to explore key contributing variables to monthly extreme precipitation intensity and frequency in six regions over the United States. The developed models effectively captured the probability and return periods of extreme precipitation, offering valuable tools for decision-making in infrastructure planning and design.

![Extreme precipitation Intensity](/assets/img/jame21792-fig-0003-m.jpg)

### Predicting future well performance for environmental remediation design using deep learning
[Publication](https://doi.org/10.1016/j.jhydrol.2023.129110)

Developed a deep learning (DL) framework with a multi-channel three-dimensional convolutional neural network (MC3D-CNN) to predict well performance and thereby assist future environmental remediation design. The framework is developed with operational and monitoring data routinely collected during P&T remedy operations, including well extraction and injection rates as well as in situ contaminant concentrations. This data-informed approach provides a flexible tool to support adaptive site management, streamline decision-making, and potentially reduce remediation time and costs. 

![3D CNN](/assets/img/3D_CNN.png)

### Approximate Mixed-Integer Programming Solution with Machine Learning Technique and Linear Programming Relaxation
[Publication](https://doi.org/10.1109/ICSGSC.2019.00-11)

Applied Classification and Regression Tree (CART) and random forest (RF) model—to obtain an linear programming relaxation(LPR)-based approximation that close to an mixed integer programming (MIP) solution without actually solving the MIP problem. This method is computationally efficient and could achieve an approximation sufficiently close to the Security constrained unit commitment(SCUC) solution with <0.15% error and ~78% reduction in the discrepancies between LPR and MIP solutions.

![MIP approx](/assets/img/MIP_pred.png)

### Probabilistic Forecasting of Generators Startups and Shutdowns in the MISO System Based on Random Forest
[Publication](https://doi.org/10.1109/PESGM41954.2020.9281926)

Built Random Forest models to predict generator startup and shutdown probabilities based on historical hourly system condition observations in the Midcontinent Independent System Operator (MISO) system; significantly reduced the number of binary commitment status variables by 90%, and therefore improve the computational efficiency of security constrained unit commitment (SCUC) solutions.

![Feature Ranking](/assets/img/FRanking.png)

### WHONDRS-GUI: a web application for global survey of surface water metabolites
[Publication](https://doi.org/10.7717/peerj.9277)

Developed an interactive [WHONDRS-GUI](https://xmlin.shinyapps.io/whondrs/) using R shiny to support data accessibility and multi-domain integration for the Worldwide Hydrobiogeochemistry Observation Network for Dynamic River Systems (WHONDRS) community. The web-based tool allows users to explore, visualize, and integrate metabolomics, microbiome, and geochemical datasets without programming requirements, which enhances research by providing an open and structured dataset, facilitating model-data integration for improved watershed function predictions.

![WHONDRS-GUI](/assets/img/GUI.png)

## Awards and Honors 
- 2024: Outstanding Performance Award,PNNL,US
- 2023: Exceptional Contribution Award, PNNL, US
- 2018: Dean's Graduate Award, University of Idaho, US
- 2013: Quality Engineer of the Year, CEME(Zhongshan) Co.Ltd., Zhongshan, China

## Publications 
1. Lin X., J. Fan, Y. Zhang, and Z. Hou. 2024. "Machine Learning Analysis of Impact of Western US Fires on Central US Hailstorms." Advances in Atmospheric Sciences 41, no. 7:1450-1462. PNNL-SA-201265. [doi:10.1007/s00376-024-3198-7](https://doi.org/10.1007/s00376-024-3198-7) 
2. Hou Z., N.D. Ward, A.N. Myers-Pigg, X. Lin, S.R. Waichler, C.A. Wiese Moore, and M.J. Norwood, et al. 2024. "Quantifying Drivers of Methane Hydrobiogeochemistry in a Tidal River Floodplain System." Water 16, no. 1:Art. No. 171. PNNL-SA-158802. [doi:10.3390/w16010171](https://doi.org/10.3390/w16010171)
3. Bao, J., X. Song, Y. Chen, Y. Fang, X. Lin, Z. Hou, ... & T. Scheibe (2024). On the transferability of residence time distributions in two 10-km long river sections with similar hydromorphic units. Journal of Hydrology, 640, 131723. [doi:10.1016/j.jhydrol.2024.131723](https://doi.org/10.1016/j.jhydrol.2024.131723)
4. Lin X., and Z. Hou. 2023. An Inventory of AI-ready Benchmark Data for US Fires, Heatwaves, and Droughts. PNNL-34891. Richland, WA: Pacific Northwest National Laboratory. An Inventory of AI-ready Benchmark Data for US Fires, Heatwaves, and Droughts. [doi:10.25584/2004956](https://doi.org/10.25584/2004956).
5. Lin X., Fan J., J. Wang, and Z. Hou. 2022. "Machine Learning of Key Variables Impacting Extreme Precipitation in Various Regions of the Contiguous United States." Journal of Advances in Modeling Earth Systems(2023). [doi: 10.1029/2022ms003334](https://doi.org/10.1029/2022MS003334)
6. Song, X., Ren, H., Hou, Z., Lin, X., Karanovic, M., Tonkin, M., Freedman, V.L., Demirkanli, I. and Mackley, R., 2023. Predicting Future Well Performance for Environmental Remediation Design using Deep Learning. Journal of Hydrology (2023). [doi: 10.1016/j.jhydrol.2023.129110](https://doi.org/10.1016/j.jhydrol.2023.129110)
7. Kaufman M.H., R.N. Ghosh, J.W. Grate, D.S. Shooltz, M. Freeman, T.M. Ball, and R. Loloee, Lin X., et al. "Dissolved oxygen sensor in an automated hyporheic sampling system reveals biogeochemical dynamics." PLoS Water (2022). [doi:10.1371/journal.pwat.0000014](https://doi.org/10.1371/journal.pwat.0000014) 
8. Lin X., Ren H, Goldman AE, Stegen JC, Scheibe TD. 2020. WHONDRS-GUI: a web application for global survey of surface water metabolites. PeerJ 8:e9277  [doi: 10.7717/peerj.9277](https://doi.org/10.7717/peerj.9277)
9. Lin X., Z Hou, Y Chen, S Rose, Y Ma, and F Pan. 2019. "Probabilistic Forecasting of Generators Startups and Shutdowns in the MISO System Based on Random Forest." In IEEE Power & Energy Society General Meeting (PESGM 2020), August 2-6, 2020, Montreal, Canada, [doi:10.1109/PESGM41954.2020.9281926](https://doi.org/10.1109/PESGM41954.2020.9281926)
10. Lin X., Z. Hou, H. Ren, and F. Pan. 2019. "Approximate Mixed-Integer Programming Solution with Machine Learning Technique and Linear Programming Relaxation." In The 3rd International Conference on Smart Grid and Smart Cities, 101-107. Berkeley, California: IEEE. PNNL-SA-141126. [doi:10.1109/ICSGSC.2019.00-11](https://doi.org/10.1109/ICSGSC.2019.00-11)
11. Fu T., Lin X., Z. Hou, and Z. Deng. 2019. "Integrating Hybrid-Clustering and Localized Regression for Time Synchronization of a Hierarchical Underwater Acoustic Sensor Array." In OCEANS 2019 MTS/IEEE, October 27-31, 2019. [doi: 10.23919/oceans40490.2019.8962752](https://doi.org/10.23919/OCEANS40490.2019.8962752)