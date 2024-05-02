<h1>HDB Resale Price Prediction (2012 to 2021)</h1>
<img src="img/cover.png" style="border: none;">
<p>Training classification models to predict HDB resale flats in Singapore</p>
<h2>Motivation</h2>
<p>In Singapore's vibrant housing market, the resale sector of the Housing and Development Board (HDB) plays a pivotal role in meeting the diverse needs of residents. However, navigating this market landscape presents a formidable challenge, characterised by the intricate interplay of myriad factors influencing resale prices. Amidst this complexity, there exists a pressing need to <strong>leverage advanced analytical techniques to unravel the underlying dynamics and provide stakeholders with the insights necessary to make informed decisions</strong>.</p> 
<p>Driven by the imperative to enhance market transparency and facilitate fair transactions, this project seeks to harness the power of machine learning and feature engineering to analyse and predict HDB resale prices accurately. By delving into the multifaceted factors shaping resale prices, we aim to develop robust predictive models that empower stakeholders with the foresight needed to navigate the market landscape confidently. Through this endeavour, we aspire to contribute to the evolution of a more transparent, efficient, and equitable housing ecosystem in Singapore.</p>
<h2>Project Goal</h3>
<p>The aim of this project is to analyse and predict Housing and Development Board (HDB) resale prices in Singapore. HDB resale prices are influenced by various factors such as the price of new HDB houses, nearby amenities, and neighbourhood crime rates. By leveraging machine learning techniques and feature engineering, we aim to identify the main factors affecting resale prices and develop predictive models to forecast these prices accurately.</p>
<h2>Methodology</h2>
<h3>1. Data Sources</h3>
<p>All raw data sources are extracted from <a href="data.gov.sg">Singapore's open data platform</a>.</p>
<h3>2. Data Extraction</h3>
We made use of `<a href="https://www.onemap.gov.sg">OneMap API</a>` to retrieve a list of coordinates of amenities and calculate the distance between amenity and HDB flat using Python `GeoPy` library.
<img src="img/data_extraction.png" style="border: none;">

