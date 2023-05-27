---
layout: post
title: API
description: How we serve our clients
image: null
nav-menu: true
show_tile: true
---

### *Commercial API is under construction.*

### **API access is available here:** [Alsace Research API](https://alsace-research-api.herokuapp.com/docs#/)

At Alsace Research, we are dedicated to providing our clients with a streamlined and efficient means of accessing our data products. To facilitate this, we are developing a state-of-the-art Commercial API that offers seamless integration and simplifies the process of incorporating our insights into your systems.

The API spans a number of industries and domains:
* Finance
* Catastrophe Modeling
* Geographic Diversification Index
* Climate Risk
* Climate Histories
* Climate Extremes 
* Geocoding
* Retail Optimization

Our data products are the result of rigorous testing and rely on proprietary models. We strive to deliver cutting-edge research and development, allowing companies to seamlessly import our data directly into their existing models and workflows.




**How our API works**

1. Input your business asset locations or street addresses in an JSON object: i.e. insured assets or real estate properties, vehicles, boats, etc.
2. Make POST command on the Alsace Research API
3. Response returns the tornado statistics: average frequency, tornado_count, event_history, fatalities_stats, injuries_stats, and magnitude_mean.
4. Run analytics across your portfolio

**An example input into the API**
![image info](/assets/images/api_input.png)

**An example response from the API**
![image info](/assets/images/api_output.png)