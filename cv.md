# Doston Kayimov

## Contacts

<ul>
  <li>GitHub: <a href="https://github.com/DostonKayimov">Doston Kayimov (DostonKayimov)</a></li>
  <li>LinkedIn: <a href="https://www.linkedin.com/in/doston-kayimov-567b5a215/">Doston Kayimov</a></li>
  <li>E-mail: kaydoston@gmail.com</li>
  <li>Phone: +998904158599</li>
</ul>

## Short bio

<p>Presently, I've been working for foreign company "POSCO International Textile" as a supply agent in Purchasing department. Although my bachelor degree is for Electrical Engineering, I found my passion at coding. So, I have been taking courses and trainings at programming languages for a year now. I have learned the basics of HTML, CSS and Python. And just a few month ago, I completed the course "Python for Data Visualization" orginized by US Embassy in Tashkent. My future plan is the mastering two programming languages: JavaScript and Python.</p>

## Skills:

HTML, CSS, VS Code, Jupyter Notebook, Codepen, Git

## Link to my project in the course "Python for Data Visualization":

<ul><li><a href="https://github.com/DostonKayimov/doston_project/blob/main/project_doston.ipynb">Graphs for International Universities</a></li></ul>

## Code samples from my project:

```

<div><p>
import matplotlib.pyplot as plt
import pandas as pd
import numpy as np

universities = ["Oxford", "Stanford", "Harvard", "Cambridge", "Yale", "Princeton", "Columbia", "Toronto", "Peking", "Melbourne"]
overall = [95.6, 94.9, 94.8, 94, 91.6, 91.5, 86.8, 86, 83.9, 78.9]
teaching = [91.3, 92.2, 94.4, 90.3, 91.9, 88.8, 85.1, 75.4, 89.6, 67.1]
research = [99.6, 96.7, 98.8, 99.2, 93.8, 92.5, 82.9, 90.9, 91.3, 76.3]
citations = [98, 99.9, 99.4, 95.6, 97.9, 98.9, 97.7, 94.5, 75.4, 90.1]
students_per_staff =[11.1, 7.4, 9.3, 11, 6, 8, 5.7, 20, 11.1, 27]

fig = plt.figure(figsize=(11, 7), dpi=200)

ax1 = plt.subplot(1,1,1)
ax1.bar(universities, students_per_staff, label = "Students per staff", color = "#15b1bf")
ax1.set_ylim(0, 50)
ax1.set_ylabel("Students", fontsize=11, weight="bold", color="#12134a")
ax1.set_xlabel("Universities", fontsize=11, weight="bold", color="#12134a")
plt.legend(fontsize="small", loc="center left")

#=======================================================================================================
for index, student in enumerate(students_per_staff):
    ax1.annotate(student, xy=(index-0.09, student+0.5), fontsize="10", weight="bold", color="#fa3939")
#=======================================================================================================

ax2 = ax1.twinx()
ax2.plot(universities, overall, "o-", label = "Overall", linewidth = 3)
ax2.plot(universities, teaching, "o-", label = "Teaching", linewidth = 3)
ax2.plot(universities, research, "o-", label = "Research", linewidth = 3)
ax2.plot(universities, citations, "o-", label = "Citations", linewidth = 3)
ax2.yaxis.grid(color = "#15b1bf", linestyle = ":", linewidth = "0.5")
ax2.set_axisbelow(True)
ax2.set_ylabel("Points (out of 100)", fontsize=11, weight="bold", color="#12134a")

ax1.spines["top"].set_linewidth(0)
ax2.spines["top"].set_linewidth(0)

plt.title("Top Universities around the world", fontsize=17, weight="bold")
plt.legend(fontsize="small")
plt.savefig("Top Universities of the world.jpg")
plt.show()

  </p></div>
```

## Work experience:

Since 2018, 2nd of April, I have been working in Purchasing department as a supply agent
for <i><b>POSCO International Textile</b>, Bukhara branch</i>.

## Education:

I graduated from Bukhara Engineering Technological Institute <i>(2013-2017)</i>

## Language:

Uzbek, Russian, English<i>(IELTS 6.0)</i>.
