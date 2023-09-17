---
layout: homepage
---

## About Me
<!-- 
I'm a <a href="https://med.nyu.edu/departments-institutes/population-health/divisions-sections-centers/biostatistics/" target="_blank"> Biostatistics</a> Ph.D. candidate at <a href="https://www.nyu.edu/" target="_blank"> New York University</a>'s <a href="https://med.nyu.edu/" target="_blank"> Grossman School of Medicine</a>, specifically within the <a href="https://med.nyu.edu/research/sackler-institute-graduate-biomedical-sciences/" target="_blank"> Vilcek institute of Biomedical Sciences</a> and the Department of <a href="https://med.nyu.edu/departments-institutes/population-health/" target="_blank"> Population Health</a>. Under the mentorship of Prof.  
working under the mentorship of Prof.<a href="https://med.nyu.edu/faculty/thaddeus-tarpey" target="_blank"> Thaddeus Tarpey</a>. My research involves developing statistical models that cater to high-dimensional complex data, such as functional and imaging data.

In the summer of 2022, I had the opportunity to work as a Data Scientist Intern at <a href="https://about.google" target="_blank"> Google</a>, where I applied my statistical skills to real-world problems. 
Prior to joining the Ph.D. program, I completed my master's degree in Biostatistics and Data Science from <a href="https://www.cornell.edu" target = "_blank"> Cornell University</a> advised by Prof. <a href= "https://www.idiaz.xyz" target = "_blank"> Iván Díaz</a>, and my bachelor's degree in International Finance from <a href="https://www.cueb.edu.cn" target = "_blank"> Capital University of Economics and Business</a>. 

Outside of academia, I began my journey as a professional swimmer at the age of 5 and went on to achieve several regional and national championships. I'm also passionate about Chinese calligraphy, and my artwork has been exhibited in top galleries and museums including the <a href="http://www.namoc.org/" target="_blank"> National Art Museum of China (Beijing)</a>. In addition, I am also interested in oil painting, and aeromodelling.
-->

Hello and welcome to my website!

I have a diverse background in social science, engineering, and data science, enabling quantitative analysis while gaining insights into social phenomena and human behavior in urban environments.

I thrive on cross-disciplinary exploration and have a strong passion for acquiring new knowledge. I hope to collaborate with researchers from various fields to address complex scientific challenges and achieve comprehensive research results in the future.

Currently, I am seeking a Ph.D. position for Fall 2024, and I believe my multidisciplinary background can offer fresh insights to your lab.

<!-- 
To learn more about my academic journey, please explore my <a href="assets/files/Coursera Machine Learning Specialization.pdf" target="_blank">Statement of Purpose</a>.
-->

## Education
**[2019.09-2022.06] Tongji University**, Shanghai, China  
<i style="color:#7b5aa6">Master of Science in Architecture</i>
- GPA: 88.5/100 (Entrance through the exam-free recommendation program)
- Awards: Academic Scholarship covering all tuition fees 2019.09-2022.06

**[2014.09-2019.06] Shandong University of Science and Technology**, Qingdao, China  
<i style="color:#7b5aa6">Bachelor of Engineering in Architecture</i>
- GPA: 90.5/100 (Rank: 1/60 for 5 years)
- Awards: First-class Scholarships in academic performance (5%, 9 times); First-class Corporate Scholarships (5%, 2 times); Design-related Competition Awards (11 times, National and International level); "Outstanding Graduate" of Shandong Province (5%); "Outstanding Student" in Science, Technology, and Innovation of school (5%)

**[2019.12] Columbia University**, New York, USA  
<i style="color:#7b5aa6">Visit Student in Graduate School of Architecture, Planning and Preservation (on site)</i>
- Attended academic meetings and workshops on the subject of urban sprawl, and delivered the final presentation of a design research project on behalf of group members (score: 90/100)


## Research Interests
<!-- 
- **Manifold Learning:** positive semi-definite manifolds learning
- **Machine Learning:** fairness AI, penalization and augmentation methods
- **Functional Data Analysis:** functional regression, and clustering methods
- **High-Dimensional Statistics:** matrix-valued regression and clustering, positive semi-definite matrices estimations
-->

- Urban Informatics, Spatial Data Science, GeoAI, Social Sensing
- Sustainable Transportation, Human Mobility and Behavior, Space-Time Analytics
- Public and Environmental Health, Urban Climate, Resilient Cities


## Research Articles
[1] **Gong, W.**, Huang, X., White, M., Langenheim, N., 2023. <a href="https://doi.org/10.3390/land12071339" target="_blank"> Walkability Perceptions and Gender Differences in Urban Fringe New Towns: A Case Study of Shanghai</a>. *Land* 12, 1339. *(SSCI Q2)*  
[2] **Gong, W.**, Jin, R., Li, T. <a href="assets/files/project1.pdf" target="_blank"> Deciphering Urban Bike-Sharing Patterns: An In-depth Analysis of Natural Environment and Visual Quality in New York's Citi Bike System</a>. *Journal of Transport Geography (Under Review, SSCI Q1)*  
[3] Zhang, X., **Gong, W.** <a href="https://doi.org/10.13717/j.cnki.ta.2021.06.025" target="_blank"> Evolution of Fire Administration Space: Analysis of Location and Architectural Form of the Fire Stations in the Concession Areas of Modern Shanghai</a>. *Time + Architecture*. 2021(06): 156-165. *(In Chinese)*

{% include_relative _includes/project1.md %}
-	Utilized multi-sources data, including sociodemographic, built environment, and natural environment factors to examine their impact on Citi Bike usage in New York City on weekdays and weekends in the year 2022.
-	Processed about 13 million trip data using Python, collected a set of 6,744 street view images through Google API, and then employed PSPNet model for semantic segmentation; processed sociodemographic data at Census Block Groups level, Points of Interest data, weather and air quality data using ArcGIS pro.
-	Applied machine learning models to establish non-linear relationships between features and bike-sharing usage at the station scale and reveal the feature importance using SHapley Additive exPlanations (SHAP) package in Python.
-	Developed multiscale geographically weighted regression (MGWR) models to capture spatial non-stationary and reveal quantitative effects of related factors at the neighborhood scale.

{% include_relative _includes/project2.md %}
-	Utilized the Network Analysis tool in ArcGIS to obtain the 15-minute walking radius for 11 communities in Shanghai’s five new towns and the central area based on the road network from Open Street Map.
-	Developed a TrueSkill-based rating system to dynamically collect audits of 325 street view images from professional students, and used DeeplabV3 and Mask R-CNN models to extract the physical features in images.
-	Conducted a clustering analysis using PCA and K-means++ algorithms of the perceived walkability scores in 11 communities and explored the characteristics of each cluster.
-	Applied Random Forest feature importance to analyze gender differences in factors influencing walkability perception and assessed the prediction performance of various machine learning models.

{% include_relative _includes/project3.md %}
-	Utilized spatial analysis methods such as Kernel Density, Standard Deviational Ellipse, and Spatial Autocorrelation to characterize the spatial and temporal evolution of courier station distribution in 2018 and 2022 at the macro scale.
-	Applied the geographically weighted regression (GWR) model to identify meso-influential factors and models that are "fit for courier stations" and evaluated the supply and demand for street-scale courier station layouts.
-	Analyzed micro-environmental characteristics "fit for courier stations" within 500m buffer zones and proposed an effectiveness evaluation of the current situation based on specific indicators.
-	Built a platform on Datlas system developed by MetroDataTech that integrates data visualization, supply and demand, and performance evaluation for courier station siting services.

{% include_relative _includes/project4.md %}
-	Applied qualitative methods to summarize the establishment, distribution, and location characteristics of fire stations in modern Shanghai, as well as the general layout, main building layout, functional composition, and architectural form.
-	Analyzed the impact of municipal fire station construction on Modern Shanghai from sociological and anthropological perspectives, focusing on urban autonomy and civil society.

{% include_relative _includes/project5.md %}
-	Analyzed the impact of urban sprawl, including the occupation of green spaces and arable land, as well as the growing separation of food production from consumption in the city, through literature review and satellite map comparisons.
-	Suggested a novel urban development framework integrating urban agriculture with the community through three distinct prototypes: agriculture + housing, shopping, and education.

{% include_relative _includes/visualization1.md %}
-	Utilized Sept. 1, 2022 and Sept. 3, 2022 (representing weekday and weekend) as examples to visualize the Origin-Destination (OD) flows of shared bicycles during both morning and evening peak hours and discern the disparities between them.
- Created dynamic visualizations of the spatio-temporal trajectories of shared bicycles on Sept. 1, 2022.



## Working and Teaching Experience

<!--
- **[Feb. 2023]** <a href="https://www.sciencedirect.com/science/article/pii/S089990072200346X" target="_blank">*Low muscle mass is associated with a higher risk of all–cause and cardiovascular disease–specific mortality in cancer survivors*</a> has been accepted by **Nutrition**. 
- **[Aug. 2021]** <a href="https://www.jmcp.org/doi/full/10.18553/jmcp.2021.27.10.1482" target="_blank">*Validation of EHR medication fill data obtained through electronic linkage with pharmacies*</a> has been accepted by the **Journal of Managed Care & Specialty Pharmacy**.
- **[Jan. 2021]** <a href="https://onlinelibrary.wiley.com/doi/abs/10.1111/jocd.13486" target="_blank">*Quantitative evaluation of rejuvenation treatment of nasolabial fold wrinkles by regression model and 3D photography*</a> has been accepted by the **Journal of Cosmetic Dermatology**.
-->
- **[2022.08-present]** Urban Designer and Planner, Tongji Architectural Design (Group) Co., Ltd.  
- **[2020.09-2021.01]** Teaching Assistant, Design Basics III in Urban Planning, Tongji University (Fall 2020) 

## Skills and Additional Information
- **Languages:** English (IELTS: 7.0), Chinese (native)
- **Spatial Data Analysis:** ArcGIS Pro, Geoda, MGWR 2.2
- **Programming:** Python for data processing, visualization, and analysis; Semantic Segmentation and Instance Segmentation of images; Machine learning models construction and evaluation
- **Additional Course Certificates:** <a href="assets/files/Coursera Machine Learning Specialization.pdf" target="_blank">Machine Learning Specialization</a> from Stanford University on Coursera (learning in process)

## At Last
“Jing excels in anything she chooses to pursue.” Over the years, numerous classmates, coworkers, and leaders with whom I've collaborated have echoed this sentiment. I believe it's not a matter of being more intelligent than others, but rather my heightened sense of focus, resolve, and purpose that sets me apart.

Throughout the past year, during the day, I've worked as an urban designer and planner at a company. However, by night, in my small rented room in the bustling city, I transform into a dedicated researcher, immersed in the world of data and technology. It's my unwavering passion, combined with my determination to relentlessly pursue my identified interests and goals, that drives me to sacrifice almost all of my evenings, weekends, entertainment, and social interactions, propelling me closer, step by step, toward my dreams.




