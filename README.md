# [Q2 2022] The Complete Pandas Bootcamp 2022 Data Science with Python

<p align="right"> <a 
href="https://stackoverflow.com/users/18680621/sam-taylor" target="_blank"><img alt="StackOverflow" 
src="https://stackoverflow-badge.vercel.app/?userID=18680621" /></a> <a 
href="https://github.com/SamTaylor92" target="_blank"><img alt="Github" 
src="https://img.shields.io/badge/GitHub-181717.svg?style=for-the-badge&logo=GitHub&logoColor=white" /></a> <a 
href="https://www.linkedin.com/in/samjamest" target="_blank"><img alt="LinkedIn" 
src="https://img.shields.io/badge/LinkedIn-0A66C2.svg?style=for-the-badge&logo=LinkedIn&logoColor=white" /></a> <a 
href="https://signal.group/#CjQKIO50NLkjJmSisbgDD4OhRj5lHG7X-SJTOl-Dn8Fkc4FpEhCYdnCVL1ok4DlVNntY3mGe" target="_blank"><img alt="Signal" src="https://img.shields.io/badge/Signal-3A76F0.svg?style=for-the-badge&logo=Signal&logoColor=white"/></a> <a 
href="mailto:samtaylor92@live.co.uk" target="_blank"><img alt="Email" src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" /></a>
</p>
<p align="right">
  
![olympics_heatmap](https://user-images.githubusercontent.com/105542266/172046085-ccd6ab7e-1e51-4bb3-bc2e-4332374b3ca7.png)
<p align="right"> [Rank of each country's success per sport]</p>
  
  
<h2> Tools</h2>
<p>
<a target="_blank"><img alt="Jupyter Notebook" src="https://img.shields.io/badge/Jupyter-F37626.svg?style=for-the-badge&logo=Jupyter&logoColor=white"/></a> 
<a target="_blank"><img alt="Python" src="https://img.shields.io/badge/Python-3776AB.svg?style=for-the-badge&logo=Python&logoColor=white"/></a> 
<a target="_blank"><img alt="Pandas" src="https://img.shields.io/badge/pandas-150458.svg?style=for-the-badge&logo=pandas&logoColor=white"/></a>
<a target="_blank"><img alt="matplotlib" src="https://img.shields.io/badge/matplotlib-13324B.svg?style=for-the-badge&logo=ChartMogul&logoColor=white"/></a>
<a target="_blank"><img alt="seaborn" src="https://img.shields.io/badge/seaborn-1F8ACB.svg?style=for-the-badge&logo=Codeforces&logoColor=white"/></a>
<a target="_blank"><img alt="scipy" src="https://img.shields.io/badge/SciPy-8CAAE6.svg?style=for-the-badge&logo=SciPy&logoColor=white"/></a>
</p>
  
## Description
Project work for the course: [The Complete Pandas Bootcamp 2022: Data Science](https://www.udemy.com/course/the-pandas-bootcamp/).  

<details open>
<summary> <h2>🔨Data aggregation project</h2> </summary>
  
This challenge asked me to apply and combine many concepts regarding `data aggregation` that I learned in the course.

It was aimed at **working with**, **manipulating** and **aggregating data**.

It tested my ability:
- to interpret and understand the underlying data
- to incorporate input from subject matter experts (in this case ficticious sports experts)
- to 'think in data structures'
<p align='right'><a href="#-tools" target="_blank">⬆</a></p>	
  
<details open>  
  
<summary> <h3> 🎯[Task] </h3> </summary>

> You're asked to compile the official Summer Olympic Games Medal Tables for all editions from 1896 to 2012.
>
> All you can use is a dataset with raw data containing over 31,000 medals (`summer.csv`) and the official medal tables for the 1996 and 1976 editions from Wikipedia. (`wik_1996.csv`, `wik_1976.csv`). 
>
> Use the two official medal tables as a reference to check whether your code produces the correct output!
>
> Your goal is to minimize the divergence between your aggregated medal tables and the official medal tables.
>
> `Divergence:`
> - Let's assume that the official number of gold medals for the United States in the 1996 edition is 44 and your code produces 46.
> - This is an absolute divergence of 2.
>
> `To do:`
> - Calculate the total absolute divergence for the 1996 and 1976 editions of the Olympics.
> - The desired outcome (divergence score) is 0!  
<p align='right'><a href="#-tools" target="_blank">⬆</a></p>	  
  
</details>  
  
<details open>
<summary> <h3>💡[Solution]</h3> </summary>

`Repository:` [(Link)](https://github.com/SamTaylor92/The-Complete-Pandas-Bootcamp-2022-Data-Science-with-Python)<br> 

<img width="1111" alt="divergence" src="https://user-images.githubusercontent.com/105542266/172053845-2c7d3703-d9b5-4d37-9755-f3240fdca310.png">
<p align='right'><a href="#-tools" target="_blank">⬆</a></p>	
  
</details>  
</details>
</details>
</details>

<details open>
<summary> <h2>🕵🏼‍♂️Exploratory data analysis</h2> </summary>
  
This challenge asked me to apply and combine many concepts regarding `exploratory data analysis` that I learned in the course.

It was aimed at **cleaning data**, **visualising data** and **hypothesis testing** with several data analyisis libraries (pandas, seaborn, matplotlib, scipy).

It tested my ability:
- to interpret and understand the underlying data
- to clean data
- to form and test hypothesis with data
- to visualise data for ease of interpretation
<p align='right'><a href="#-tools" target="_blank">⬆</a></p>	

<details open>  
  
<summary> <h3> 🎯[Task] </h3> </summary>

> Now that you've aggregated your datasets, you're asked to perform exploratory data analysis on the official Summer Olympic Games Medal Tables for all editions from 1896 to 2012.
>
> There are three datasets:
> - summer.csv
> - winter.csv
> - dictionary.csv
>
> Your goal is to:
> - Import the data
> - Clean the data 
>   - Merge tables
>   - Deal with missing values
>   - Convert data to correct type
> - Analyse the dataset
>   - Which are the most successful countries?
>   - Summer vs winter games - does country location matter?
>   - Men vs women - does country culture matter?
>   - Countries vs sports - do traditions matter?  
> - Test hypothesis
>   - Relationship between total medals and population
>   - Relationship between total medals and participation
>   - Relationship between total medals and GDP
<p align='right'><a href="#-tools" target="_blank">⬆</a></p>	
  
</details>  
  
<details open>
<summary> <h3>💡[Solution]</h3> </summary>

`Repository:` [(Link)](https://github.com/SamTaylor92/The-Complete-Pandas-Bootcamp-2022-Data-Science-with-Python)<br> 

<img width="898" alt="summer_versus_winter" src="https://user-images.githubusercontent.com/105542266/172053745-7682e208-1ce2-45c0-9c0f-3b04f721aeb3.png">
<p align='right'><a href="#-tools" target="_blank">⬆</a></p>	
  
</details>  
</details>
</details>
</details>

<details open>
<summary> <h3>📚[Reference material]</h3> </summary>
  
- [x] [The Complete Pandas Bootcamp 2022: Data Science](https://www.udemy.com/course/the-pandas-bootcamp/)
<p align='right'><a href="#-tools" target="_blank">⬆</a></p>	

</details>
</details>

</p>

</br></br>
© 2022 GitHub, Inc.
Terms
Privacy
