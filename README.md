# Assignment 2: Protests
In recent years the United States has experienced a surge of protests, in support of Black Lives Matter, gender equity, and many other social or political issues.

In this assignment, you will work with data from [Count Love](https://countlove.org/), data that is ocassionally [cited](https://www.nytimes.com/2020/08/28/us/black-lives-matter-protest.html) by the _New York Times_ when reporting on US demonstrations.

Through this assignment, you will be able to answer questions about protests, including:

* What were the most attended and least attended protests in the US in the last 5 years?
* How many protests occurred in Washington state?
* How did the number of protests in 2019 compare to 2020, and why?
* Why are people protesting in the US? What are the biggest motivators?

## Learning objectives
By completing the assignment, you will develop or skills for:

- **Version control** tools for managing code (git and GitHub)
- Writing documents with **markdown** syntax
- Coding in R
- Thinking critcally about data.

# 1. Critical Analysis & Reflection: Before You Code

Before diving into this (or any) dataset, it's important to know where the data came from, and it's important to have or to seek out _domain familiarity_ — that is, knowledge about the topic of the dataset. Sometimes the topic is very narrow; more often it is expansive, as in the case of CountLove. We don't want to be "strangers in the dataset," as Catherine D'Ignazio and Lauren Klein describe it. To get more familiar, we are going to begin by doing some background reading.

**Note:** Please write your answers below under the heading "Your Responses and Reflections."

- First, please read [this FAQ](https://countlove.org/faq.html) from the CountLove website and the opening of [this blog post](https://www.tommyleung.com/countLove/index.htm).  **(R1a)** Based on the information in these pieces, why did the creators start collecting the CountLove data?

- Next, we would like you to read this [New York Times piece that uses CountLove data](https://www.nytimes.com/interactive/2020/06/13/us/george-floyd-protests-cities-photos.html) and that describes the Black Lives Matter protests that occurred in the summer of 2020. **(R1b)** Please summarize the main point or argument of this article.

Next, we're going to reflect about who collected this data, and what's actually inside it. 

**(R1c)** Who collected and shared the CountLove data, and what do they do for a living?

**(R1d)** As Klein and D'Ignazio remind us, when it comes to data, "what gets counted counts." What types of demonstrations does CountLove include in their data, and what types do they exclude? 

**(R1e)** How and where does CountLove get their data about the protests? 

**(R1f)** How does CountLove make their estimates about the number of people who attended a protest? What potential problems might arise from this method of estimation? 

**(R1g)** What are two central values of Count Love? Name and briefly describe them. (See the Envisioning Cards for a defintion of "value".)

**(R1h)** Name and briefly describe one direct stakeholder and one indirect stakeholder (See the Envisioning Cards)? 

# 2. Coding in R: Parts 1-6
**Instructions**. Assignment instructions and prompts are in this file: [analysis.R](analysis.R).

**Coding and reflection prompts**. You will find two kinds of prompts in [analysis.R](analysis.R):

* *Coding prompts*, which prompt you to write R code in [analysis.R](analysis.R).
* *Reflection prompts*, which prompt you to think and write in English below, in this file (README.md).

**Formatting Your Responses and Reflections**.

* When formatting your written responses and reflections below, please *retain* all
reflection prompt IDs (e.g., R1a, R2a, etc.).
* Fill in the elipses (...) with your own words. 
* Remove expected word counts.
* To write clearly, use markdown code appropriately (e.g., **bold**, _italics_, and `code`). As appropriate, include images, links, and so forth.

**Questions?** As always, please post on Teams or ask your Instructor or Teaching Assistant.

:computer: Good coding!
   :writing_hand: Good critical thinking!
      :smile: Good-luck!

(_Updated: October 2022, Your Teaching Team_)

# 3. Critical Analysis & Reflection: After You Code

In the second chapter of *Data Feminism*, Klein and D'Ignazio describe 4 ways that data scientists can challenge power and take action:
> Taking action can itself take many forms, and in this chapter we offer four starting points:  
> (1) Collect: Compiling counterdata—in the face of missing data or institutional neglect—offers a powerful starting point as we see in the example of the DGEI, or in María Salguero’s femicide maps discussed in chapter 1.  
> (2) Analyze: Challenging power often requires demonstrating inequitable outcomes across groups, and new computational methods are being developed to audit opaque algorithms and hold institutions accountable.  
> (3) Imagine: We cannot only focus on inequitable outcomes, because then we will never get to the root cause of injustice. In order to truly dismantle power, we have to imagine our end point not as “fairness,” but as co-liberation.  
> (4) Teach: The identities of data scientists matter, so how might we engage and empower newcomers to the field in order to shift the demographics and cultivate the next generation of data feminists?  

**(R1h)** How does the CountLove project embody one or more of these 4 forms of challenging power? 

**(R1i)** What is the most interesting or surprising thing you learned from this analysis? Please answer in at least 2-3 sentences (2 points)

**(R1j)** What is a kind of analysis that you would like to do or that would be interesting to do with the CountLove data that you don't have the time or skills to accomplish at this moment? Please answer in at least 2-3 sentences (2 points)

## Your Responses and Reflections

### Critical Analysis & Reflection: Before You Code (questions above)

* **(R1a)** The creators started collecting the CountLove data in hopes of keeping factual records of ongoing protests to make data more accessible so it can help citizens, journalists, and politicians, and also historially document protests related to civil rights, immigrations, racial injustice and many other importnat issues.
* **(R1b)** The main point of this article was to show how the BLM movement was reached in every state and corner of the United States and the importance that it showed in every area and the people of our country.
* **(R1c)** Tommy Leung and Nathan Perkins collect and share the CountLove data and are enginners and scientists that have a focus in public policy and civic responsibility.
* **(R1d)** The type of demonstrations CountLove includes are public displays of protest that aren't part of "regular business", and they exclude awareness events, commemorative celebrations, historic reenactments, fundrasising events, townhalls, or political campaign rallies.
* **(R1e)** CountLove gets their data about protests through newspapers and television sites, and that data is extracted through their software that automates the most time-consuming error-prone parts of the workflow.
* **(R1f)** CountLove uses a conservative count approach, meaning that they interpet "a dozen" as 10, "dozens" as 20, "hundreds" as 100, and so on. A potential problem with this method is that the count can be off or provide a misconception about the amount, because "hundreds" can mean a wide range of counts.
* **(R1g)**  
   * Accessibility: Searching through individual records can get tedious and getting this information in a quick and organized way is important to CountLove.
   * Compassion: Keeping these records and making them accessible can help citizens, journalists, and politicians to share ideas of empathy and kindness. Using this data for the betterment of the country is important to CountLove.
* **(R1h)** 
   * Direct stakeholder: Journalists who use this data in their writing to show evidence of something or a visualization.
   * Indirect stakeholder: A citizen can be an indirect stakeholder of CountLove as they could benefit from the availability of data and awareness it can bring.

### Part 3: Locations (`analysis.R`)
* **(R3a)** The number of protests in Washington State does not surprise me. I think that Washington State has many people who are activists and passionate on social topics and issues which is why the number of protests is what it is.
* **(R3b)** I think sapply() is amazing because it's able to display a function in a very clean and readable way, and it is very easy to implement into datasets.
* **(R3c)** I noticed that casing was an issue in my data quality. For example, there's two different places for Washington state, one being "WA" and the other "wA". I would change this by taking casing into account when creating the uniq_states vector.

### Critical Analysis & Reflection: After You Code (questions above)
* **(R7h)** ... (100 words or more)
* **(R7i)** ... (50 words or more)
* **(R7j)** ... (50 words or more)
