---
layout: default
---



<link rel="stylesheet" type="text/css" href="https://cdn.datatables.net/1.10.21/css/jquery.dataTables.min.css" />
<script src="https://code.jquery.com/jquery-3.5.1.js"></script>
<script src="https://cdn.datatables.net/1.10.21/js/jquery.dataTables.min.js"></script>  


# SPRING 2023

## Class Information

Item                     | Section 0040                 
------------------------ | -----------                  
Schedule                 | Tue/Thursday 2:20 PM - 3:40 PM EST
Location                 | Zoom. Details on Carmen. Some lectures will be in person and zoom.
Professor                | Greg Ryslik / ryslik DOT 1 AT osu DOT edu
Professor Office Hours   | Fridays (2:20 - 3:40 PM) - via zoom. Details on Carmen. Contact me ahead of time if you plan to attend.
TA                       | Xiang Li (li.3880@osu.edu)
TA Office Hours          | TBD                         
Discord Link             | https://discord.gg/vFSFu6GZ



## Description: 
This class aims to introduce the knowledge discovery process, key data mining techniques, efficient high performance mining algorithms and provide a broad based exposure to the applications of data mining. This webpage will serve as the source of information for the course. We will post all python/R, jupyter notebooks, pdfs, lecture notes and other information here.
	
It is highly encouraged that you simply fork this entire repo and then just sync updates periodically. This will provide you the easiest access to all the class materials at once. For more information on this process, you can see the documentation [here](https://docs.github.com/en/get-started/quickstart/fork-a-repo). 

## Grading Plan: 
1. Homework x5: 60%
2. Participation/Attendance: 5%
3. Midterm Exam: 15%
4. Final Exam: 20%
5. No course project

There might be tentative bonus points assigned for harder math or cs problems. Max would be at most 3%. 

## Textbooks:
No one textbook, please feel free to refer to the below


1. [(Primary) Data Mining: Concepts and Techniques, 3rd edition, Morgan Kaufmann, Jiawei Han, Micheline Kamber, and Jian Pei.](http://hanj.cs.illinois.edu/bk3/)
2. [(Primary) Introduction to Data Mining, Pang-Ning Tan, Michael Steinbach, and Vipin Kumar](http://www-users.cs.umn.edu/~kumar/dmbook/index.php)
3. [(Supplementary) Data Mining Analysis and Concepts (Online version available), Mohammed J. Zaki and Wagner Meira, Jr.](http://www.dataminingbook.info/pmwiki.php/Main/BookDownload)
4. [(Supplementary) Mining of Massive Datasets (Online version available), Jure Leskovec, Anand Rajaraman and Jeffrey Ullman](http://www.mmds.org/)
5. [(Supplementary) Machine Learning, Tom Mitchell](http://www.cs.cmu.edu/~tom/mlbook.html)
6. [(Supplementary) Pattern Recognition and Machine Learning, Christopher M. Bishop](http://research.microsoft.com/en-us/um/people/cmbishop/prml/)

## Class course

<table class="display" border=1 frame=sides rules=all>
  {% for row in site.data.Syllabus %}
    {% if forloop.first %}
    <tr>
      {% for pair in row %}
        <th>{{ pair[0] }}</th>
      {% endfor %}
    </tr>
    {% endif %}

    {% tablerow pair in row %}
      {{ 	pair[1] }}
    {% endtablerow %}
  {% endfor %}
</table>

## Formal Syllabus
The syllabus with all the academic policies can be found [here](/cse5243/course_materials/syllabus/CSE5243-GRyslik-V1.docx). 
