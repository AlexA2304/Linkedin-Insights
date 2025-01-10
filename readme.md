# Career Navigation Powered by Insights Derived From 1.3 Million LinkedIn Job Postings
---

## Description:
This project aims to help you navigate your chosen career path by deriving valuable career insights from the 2024 LinkedIn job market. Through the derivation and visualization of industry growth across the US, the most popular skills and skill sets in each industry, and the proportional growth of each industry, this project helps users discover trends that help them plan for success. Over 1 million job postings are analyzed to provide personal insights into the broad trends concerning each of the 18 largest industries identified using iteratively refined keyword mapping.

## Questions This Tool Will Help Answer:
**Based On My Industry...**
- In what regions and cities are jobs growing the most?
- What are the most frequently sought-after skills for the jobs that I want?
- Which skills are more valuable to employers when paired with each other?

## Example Using the Technology Industry
### Top Skills in Tech:
- The insights that can be revealed with this tool have numerous real-world applications for job-seekers. As an aspiring SWE, I have an opportunity to gain clear and actionable insights into some of the most important determining factors for success in a tech career. For example, I now have a list of the most in-demand skills in tech like `SQL`, `Python`, and `Java`, that I can use as a guide to attain skills that matter most to employers.

![Top Tech Skills](./Graphs/techSkills.png)
---
### Industry Proportions of Job Market:
- I also get a pie chart that outlines industry growth for each of the 18 identified industries, informing my understanding of how demand for new employees has grown in the tech industry in proportion to others. I now know that the tech industry made up roughly `5.7%` of categorized postings, while other industries like 'Healthcare' made up roughly `21.4%` of postings.

![Pie Chart](./Graphs/pie.png)
---
### Apriori Determined Popular Skillsets:
- In addition, the tool offers insight into which industry-specific skills are more valuable when paired together such as `Java, SQL, Python`, and `AWS, Kubernetes, Docker`, offering me the power to invest my time more wisely by honing complimentary skills.

![Apriori](./Graphs/techApriori.png)
---
### National Tech Hotspots:
-  With even more help from this tool and its ability to spatially map industry growth, I also gain a nuanced understanding of where I can expect to find work. Examining the national scale industry boom map, it's clear that tech jobs are concentrated in the eastern and western continental United States and Texas, in cities like `San Francisco, California`, `New York City, New York`, and `Austin, Texas`.

![National Hotspots](./Graphs/UShotspots.png)
---
### California Tech Hotspots:
- California appears to be the densest state for new tech jobs, so I chose it as the subject for my state-level analysis, Where I can see that the most tech industry opportunities are in `San Francisco`, `San Diego`, `San Jose`, `Los Angeles`, and `Irvine`.

![California Hotspots](./Graphs/CAhotspots.png)
---

## Link to Video Presentation:
https://www.youtube.com/watch?v=SaSj2wXWLgM

## Setup and Use:
1. Clone the repository to your local machine or download and extract the .zip file above.
2. Create a new Python Virtual Environment with:

```
python3 -m venv myenv
source myenv/bin/activate
```
3. With your Virtual Environment active, run the following command to install all required dependencies:
```
pip install numpy pandas scipy nltk matplotlib seaborn mlxtend geopandas ipython
```
4. Refer to the 'Data Sets' section for which data sets you must install.
5. Access the Jupyter Notebook and run each cell, inputting your industry of choice for tailored insights.
6. Enjoy!

### Data Sets: (Download to the root directory of your cloned repository)
- **[1.3 M Linkedin Jobs & Skills (2024)](https://www.kaggle.com/datasets/asaniczka/1-3m-linkedin-jobs-and-skills-2024)!**
    - job_skills.csv
    - linkedin_job_postings.csv
- **[United States Cities Database](https://simplemaps.com/data/us-cities)!**
    - uscities.csv
