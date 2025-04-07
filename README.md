# SmartStudy – AI-driven study planner

Final project for the Building AI course

## Summary

SmartStudy is an AI assistant that helps students create personalized study plans based on their deadlines, workload and available time.  
Building AI course project

## Background

Many students struggle with planning their studies, especially when taking multiple courses. This often leads to missed deadlines, stress and burnout. A tool like SmartStudy could improve both performance and well-being.

* difficulty prioritizing assignments  
* lack of structured study schedule  
* increased stress and inefficiency  

## How is it used?

Students input their course details, deadlines and available study time. The AI generates a realistic day-by-day plan. It can be updated if something changes. The solution is useful for university and high school students, especially those studying independently or online.

![Cat](https://upload.wikimedia.org/wikipedia/commons/5/5e/Sleeping_cat_on_her_back.jpg)

This is how you create code examples:
```
def main():
   countries = ['Denmark', 'Finland', 'Iceland', 'Norway', 'Sweden']
   pop = [5615000, 5439000, 324000, 5080000, 9609000]   # not actually needed in this exercise...
   fishers = [1891, 2652, 3800, 11611, 1757]

   totPop = sum(pop)
   totFish = sum(fishers)

   # write your solution here

   for i in range(len(countries)):
      print("%s %.2f%%" % (countries[i], 100.0))    # current just prints 100%

main()
```

## Data sources and AI methods

The project uses self-reported user input (deadlines, time availability, topics). It could apply rule-based planning and basic optimization algorithms, with potential to expand to reinforcement learning for dynamic adjustment.

| Data source        | Use case                      |
|--------------------|-------------------------------|
| User input         | Task deadlines and workload    |
| Scheduling logic   | Generate optimized study plan  |

## Challenges

The project does not solve motivational issues or guarantee task completion. It relies on users providing accurate information. Ethically, it must avoid overloading users or promoting unrealistic schedules.

## What next?

The project could evolve into a mobile app with notifications and adaptive learning based on user behavior. Collaboration with students and UX designers would help refine the tool.

## Acknowledgments

* Inspired by common challenges among university students  
* Idea and text written originally for the Building AI course  
* [Sleeping Cat on Her Back by Umberto Salvagnin](https://commons.wikimedia.org/wiki/File:Sleeping_cat_on_her_back.jpg#filelinks) / [CC BY 2.0](https://creativecommons.org/licenses/by/2.0)
