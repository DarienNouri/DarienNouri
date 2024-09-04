

<div style="display: flex; align-items: center; justify-content: center;">
  <img src="profile_pic.png" width="100" style="margin-right: 20px;"/>
  <h1 style="margin: 0;"><strong>Hi there, I'm Darien Nouri 👋</strong></h1>
</div>

<br>

<div align="center">
    📚 Completed my undergraduate at New York University in both Data Science and Computer Science</strong>
</div>
</p>




<br>

<!-- <img src="https://readme-stats-contributions-ov7r.vercel.app/api?username=dariennouri&count_private=true&include_all_commits=true&theme=tokyonight&hide=prs,issues,contribs" alt="Darien's GitHub stats" width="400" style="margin-bottom: 10px;"/> -->
<div style="display: flex; flex-direction: column; align-items: center; justify-content: center;">
  <a href="http://www.github.com/DarienNouri">
    <img src="https://github-readme-streak-stats.herokuapp.com/?user=DarienNouri&theme=tokyonight" />
  </a>
</div>

<br>
<div align="center">
  <strong>Email:</strong> <a href="mailto:nouri.darien@gmail.com">nouri.darien@gmail.com</a> | <a href="mailto:dan9232@nyu.edu">dan9232@nyu.edu</a>
</div>

<br>

<div id="badges" align="center">
  <a href="https://www.linkedin.com/in/darien-nouri" target="_blank" rel="noreferrer" style="margin-right: 10px;">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/linkedin-dark.svg" />
      <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/linkedin.svg" />
      <img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/linkedin.svg" width="32" height="32" />
    </picture>
  </a>
  <a href="https://www.github.com/DarienNouri" target="_blank" rel="noreferrer" style="margin-right: 10px;">
    <picture>
      <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/github-dark.svg" />
      <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/github.svg" />
      <img src="https://raw.githubusercontent.com/danielcranney/readme-generator/main/public/icons/socials/github.svg" width="32" height="32" />
    </picture>
  </a>
  <img src="https://komarev.com/ghpvc/?username=DarienNouri&style=for-the-badge&label=VIEWS" alt="Pageview Badge" style="margin-right: 20px;"/>
</div>

<hr>

## 🔍 Featured Projects

### 1. Impact of ML Model Complexity on Pairs Trading Optimization

**Objective:** Investigated the relationship between ML model complexity and forecasting accuracy for stock pair spread movements, with a focus on optimizing trading performance.

- Led research investigating the relationship between ML model complexity and forecasting accuracy for stock pair spread movements, with a focus on optimizing trading performance.
- Engineered a rich 280-feature set, including Refinitiv API-derived technical indicators, custom-scraped news headlines with BERT-based sentiment analysis, and Bloomberg Twitter sentiment data.
- Evaluated model performance across the complexity spectrum: from simple Generalized Linear Models (GLMs) to advanced neural networks, including Gradient Boosting Machines (GBMs), Random Forests (RF), Vanilla LSTM (~50k parameters), Hyperparameter-tuned LSTM (2M+ parameters), and Bidirectional LSTM with dropout.
- Developed a backtesting framework incorporating Bayesian-adjusted mean reversion strategies, achieving 80.75% annualized returns with tuned LSTM model—an average 105% improvement over non-deep learning models.
- [GitHub Repository](https://github.com/DarienNouri/Trading-Strategy-Project)

### 2. Urban Dynamics and Real Estate Markets: Enhancing Market Forecasts with Non-Traditional Data

**Objective:** Explored the predictive power of non-traditional urban data sources in forecasting real estate trends and Real Estate Investment Trust (REIT) performance.

- Led research on the efficacy of non-traditional urban data in predicting real estate trends and REIT performance, analyzing datasets such as Citibike usage, building complaints, business operations, health inspections, evictions, etc.
- Architected a scalable, cloud-based ecosystem to process and analyze terabytes of diverse datasets, leveraging technologies like MongoDB, AWS services, and distributed computing frameworks such as Dask and PyArrow for efficient data handling.
- Engineered high-performance data acquisition systems, including a web scraper for MLS data processing over 1 million listings daily, and a parallel ingestion framework for more than 1 billion historical Citibike rides.
- Integrated Granger-causality optimized alternative data sources, improving market index forecasts by 25% and REIT predictions by 34.2%.
- Designed an interactive Streamlit application for non-technical stakeholders, allowing intuitive exploration of correlations between alternative data and market trends. ([Feature Explorer Demo Render](https://darien-public-assets.s3.amazonaws.com/feature_exploration_streamlit_app_render.pdf))
- [GitHub Repository](https://github.com/DarienNouri/alt-data-real-estate-predictions) | [IEEE Report (Pending Submission)](https://darien-public-assets.s3.amazonaws.com/Propertize_IEEE_Conference_Final.pdf)

### 3. Real Estate Valuator & Market Analysis Frameworks

**Objective:** Developed a multi-model machine learning framework to valuate residential properties and forecast sale probabilities, integrating data from diverse sources.

- Engineered a multi-model ML framework utilizing ensemble and gradient boosting methods for residential property valuation and sale probability forecasting, integrating data from Zillow, Yelp, and other relevant sources.
- Developed an interactive Streamlit application that allows users to access real-time property valuations, explore detailed market data, and visualize macroeconomic trends in the real estate sector.
- [Valuation App Demo](https://demo.propertize.ai/) | [Market Analysis App Demo](https://propertytrends.darien.ai/) | [Analysis GitHub Repository](https://github.com/DarienNouri/Streamlit-RE-Analysis-Web-App)

### 4. Web App Deployment Service

**Objective:** Automated the deployment of Python-based web applications on AWS EC2 instances, streamlining continuous integration and delivery processes.

- Developed a scalable and automated deployment system for Python-based web applications (Dash, Streamlit) on AWS EC2 instances, enhancing the efficiency of continuous integration and delivery (CI/CD).
- Integrated a GitHub webhook-based deployment system that automatically triggers deployments upon code pushes, ensuring seamless and streamlined deployment of MVPs and new features.
- Leveraged PM2 for continuous process management and Nginx as a reverse proxy, providing high availability and load balancing for deployed applications.
- Incorporated dynamic Nginx configuration generation based on deployed applications, enabling the dynamic management of custom domains and routing rules.
- [GitHub Repository](https://github.com/DarienNouri/auto-ec2-webapp-deployment-service)

### 5. Embedding-Based Clustering of Political News Headlines

**Objective:** Applied NLP techniques to classify the political orientation of news headlines using advanced embedding and clustering methods.

- Implemented text preprocessing, feature extraction, and clustering algorithms, including Spectral Clustering and K-Means, to classify the political orientation of news headlines.
- Utilized BERT models for text embedding, providing a rich representation of the textual data for clustering purposes.
- Explored dimensionality reduction techniques like PCA and t-SNE for effective visualization of high-dimensional data, enhancing the interpretability of clustering results.
- [GitHub Repository](https://github.com/DarienNouri/NLP-Document-Classification)

### 6. Python-Based Web Scrapers

**Objective:** Developed high-performance web scrapers for automating data extraction from various online platforms, supporting various projects and research initiatives.

- **Zillow Scraper:** Built a high-performance web scraper using Azure, capable of extracting over 2 million property listings per scrape on a weekly automated schedule. [GitHub Repository](https://github.com/DarienNouri/Fast-Zillow-API-Scraper)
- **LinkedIn Scraper:** Created a scraper for LinkedIn to extract data from both company and user profiles, gathering information such as company posts, user experiences, and education. [GitHub Repository](https://github.com/DarienNouri/LinkedIn-Scraper/tree/main)
- **Yelp Scraper:** Developed a Selenium-based web scraper to extract restaurant data, including information on health ratings, review counts, and business details. [GitHub Repository](https://github.com/DarienNouri/Yelp-API)

---