## Introducing Cloud Analytics on Microsoft Azure

According to Dresner Advisory Service in their 2019 Cloud Computing and Business Intelligence Market Study, 48% (which is an all-time-high) of organizations say business intelligence on cloud is either “critical” or “very important” in conducting their business operations. In this same research, the sales and marketing teams are the ones who gets the most value out of analytics. 

As businesses grow, they generate massive amounts of data every day. These data come from different sources such as mobile phones, IoT (Internet of Things) sensors, and various SAAS (Software-as-a-Service) products such as CRMs. Enterprise and businesses need scale and modernise their data architecture and infrastructure in order to cope up with this demand to stay competitive in their respective industries. 

Adopting cloud scale analytics is the go to strategy for this growth. Instead of managing your own data center, harnessing the power of cloud allows your business to be more accessible to your users. With the help of a cloud service provider like Microsoft Azure, you can accelerate your data analytics practices without the limitations of your IT infrastructure. The game has changed in terms of maintaining this infrastructure, as “data lakes” and the cloud data warehouse are capable of storing and maintaining massive amounts of data. 

Simply gathering data does not add value to your business; you need to derive insights from it and help your business grow using data analytics. Data analytics provides you the capability to understand your business and customers better. By applying various data science concepts such as machine learning, regression analysis, classification algorithms, and time series forecasting, you can test your hypothesis and create a data-driven decision for the future. However one of the continuous challenges is how can you derive this analytical modeling capabilities in faster times if you have billions of rows of data? This is where having a modern data warehouse and data pipeline can help (more on this in the next sections).

There are a number of ways data analytics can help your business thrive. In the case of a retail industry, if you understand your customers better, you will have a better idea on what products you should sell, where to sell it, when to sell it and how to sell it. For the public sector, data analytics is helping fight crimes by providing more informed risk assessments based on historical criminal intelligence. Another example is how manufacturing industries have modernised their businesses by using various sensors and data points to better track and monitor their assets and equipment: are the assets of good health? Do they need replacement? 

In this lesson, we will cover fundamental topics on power of data with Big Data analytics, the Internet of Things (IoT), Machine Learning (ML) and Artificial Intelligence (AI), and DataOps. We will also understand why Microsoft Azure is a right platform for performing analytics on cloud. Lastly, we will tackle the fundamental concepts of a modern data warehouse and data pipelines.

### The Power of Data


As a consumer, data has changed the way we interact on our day to day lives. In the entertainment industry, we can now get a customized experience such as recommended videos (TV Shows, Movies, and online clips) based on our interests and historical activities; it is easier now to discover music that is similar to your favourites and understand what are popular and trending. With the increase of digitisation of our health data such as adoption of wearable devices like smart watches (fitness trackers), we now get an improved health services by having the ability to monitor our health status; as well as getting tailored recommendations on how to improve our overall health.

According to IDC (International Data Corporation), by 2025: 

- more than 150 billion devices will be connected across the globe. 
- Six billion consumers will interact with data every day by 2025, representing 75% of the world’s population. 
- IoT devices will generate more than 90 zettabytes (1 zettabyte is 1 billion terabytes) of data.
- Nearly 60% of the 175 zettabytes of existing data will be created and managed by enterprise organizations (compared to 30% in 2015).
- An average connected person anywhere in the world will interact with their connected devices more than 4, 900 times per day (one interaction every 18 seconds).

[Sources](https://www.seagate.com/files/www-content/our-story/trends/files/idc-seagate-dataage-whitepaper.pdf)
 
This data is massive, and the term **Big data** has been a popular term that describes harnessing the power of this data at scale.

### This is sample code file

```/* HelloWorld.java*/
public class HelloWorld
{
	public static void main(String[] args) {
		System.out.println("Hello World!");
	}
}
```

```markdown
Syntax highlighted code block
# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/prashantmishrapackt/PAAS_tryout_Github_project/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
