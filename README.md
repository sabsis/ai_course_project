# AI Course Project

Final project for the Building AI course

## Summary

This project is about getting more familiar with AI, coding, and different software tools. I aim to create a simple application that can help users analyze and visualize data effectively, making AI more accessible to non-technical users.

## Background

This project addresses several critical problems:

* **Inefficient data processing:** Many small businesses struggle to analyze data quickly due to limited resources.
* **User accessibility:** Non-technical users often find it challenging to use existing AI tools, which can hinder decision-making.
* **Lack of insights:** Businesses often miss out on valuable insights that AI could provide if only they had the right tools.

These issues are quite common, especially among startups and small enterprises where resources are often constrained. My personal motivation comes from my experiences working with small teams that rely heavily on data but lack the tools to interpret it effectively. This topic is important as AI has the potential to revolutionize how we approach problems and make decisions in various fields.

## How is it used?

The solution will be implemented as a web-based application that small to medium-sized enterprises can use to integrate AI into their operations. It is particularly needed in fast-paced environments, such as during business meetings or project planning sessions, where quick data analysis is essential. The primary users will include entrepreneurs, project managers, and data analysts, who all have unique needs for intuitive tools that provide clear insights without requiring deep technical expertise.

![Data Analysis](https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg)

If you need to resize images, you have to use an HTML tag, like this:
<img src="https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg" width="300">

This is how you create code examples:
```python
def main():
   countries = ['Denmark', 'Finland', 'Iceland', 'Norway', 'Sweden']
   pop = [5615000, 5439000, 324000, 5080000, 9609000]   # not actually needed in this exercise...
   fishers = [1891, 2652, 3800, 11611, 1757]

   totPop = sum(pop)
   totFish = sum(fishers)

   # write your solution here
   for i in range(len(countries)):
      print("%s %.2f%%" % (countries[i], (fishers[i] / totFish) * 100))

main()
```


## Data sources and AI methods
Where does your data come from? Do you collect it yourself or do you use data collected by someone else?
If you need to use links, here's an example:
[Twitter API](https://developer.twitter.com/en/docs)

| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |

## Challenges

What does your project _not_ solve? Which limitations and ethical considerations should be taken into account when deploying a solution like this?

## What next?

How could your project grow and become something even more? What kind of skills, what kind of assistance would you  need to move on? 


## Acknowledgments

* list here the sources of inspiration 
* do not use code, images, data etc. from others without permission
* when you have permission to use other people's materials, always mention the original creator and the open source / Creative Commons licence they've used
  <br>For example: [Sleeping Cat on Her Back by Umberto Salvagnin](https://commons.wikimedia.org/wiki/File:Sleeping_cat_on_her_back.jpg#filelinks) / [CC BY 2.0](https://creativecommons.org/licenses/by/2.0)
* etc
