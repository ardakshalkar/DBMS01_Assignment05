# question 01
---
**P01.A** Count all grades from database `University`, and display amount of all letter grades.

|Letter Grade|Num|
|------------|--:|
|A|111|
|B|152|
|C|137|
|D|96|
|F|504|

**Practice instructor may give extra task during practice hour.**




# question 02
---
**P02.A** From database `university` display each row (with all columns), add one more column which shows average for the course_id, order result by student_id.

|id|student_id|grade|course_id|AVG_Grades|
|--|--:|--:|--:|--:|
|330|1|28|1|46.26190476190476|
|628|1|63|1|46.26190476190476|
|862|1|67|1|46.26190476190476|
|369|1|84|2|49.1063829787234|
|681|1|100|2|49.1063829787234|
|...|...|...|...|...|
|629|20|71|20|48.361702127659576|
  
---

**P02.B** From table rental output rental information (such as rental_id, customer_id, rental_date), also add one more column which will show how much items were rent that day.
|rental_id|rental_date|inventory_id|customer_id|overall in day|
|--:|-----------|--:|--:|--:|
|1|2005-05-24 22:53:30.000|367|130|8|
|2|2005-05-24 22:54:33.000|1525|459|8|
|3|2005-05-24 23:03:39.000|1711|408|8|
|4|2005-05-24 23:04:41.000|2452|333|8|
|5|2005-05-24 23:05:21.000|2079|222|8|
|...|...|...|...|...|
|15966|2006-02-14 15:16:03.000|4472|374|182|

---

**P02.C** In `university` database display grades with one extra column, which shows ranking of student in current course regarding year, and semester.

|id|course_id|student_id|year|semester|grade|row_number|
|--:|--:|--:|----|--------|--:|--:|
|867|1|4|2019|fall|96|1|
|765|1|17|2019|fall|34|2|
|268|1|4|2019|spring|88|1|
|136|1|20|2019|spring|31|2|
|128|1|6|2019|summer|88|1|
|...|...|...|...|...|...|...|
|683|20|11|2021|summer|2|10|




# question 03
**P03.A** Show the best student (show all best students if there are many students with best score) for each course (courses considered different for each year and semester)  
Show name of course, and name and surname of student.  
Order result by `title` of course
|Title|year|semester|student|grade|
|-----|----|--------|----------------------------------|-----|
|Algorithms 1|2019|fall|Gelya Rack|60|
|Algorithms 1|2019|spring|Selina Stockford|92|
|Algorithms 1|2019|spring|Hayes Tregensoe|92|
|Algorithms 1|2019|summer|Coraline Woodrough|75|
|Algorithms 1|2020|fall|Webster Middle|78|
|...|...|...|...|...|
|Web technologies|2021|summer|Briano Algore|60|


**P03.B** Show all courses and number of As, Bs and etc, show also ratio of As in current course to all course's As, and same for all other grades.

|Title|As|As ratio|Bs|Bs ratio|Cs|Cs ratio|Ds|Ds ratio|Fs|Fs ratio|
|-----|--|--------|--|--------|--|--------|--|--------|--|--------|
|Mathematics 1|4|3.6036036036036037|6|3.9473684210526314|5|3.64963503649635|1|1.0416666666666665|26|5.158730158730158|
|Mathematics 2|4|3.6036036036036037|9|5.921052631578947|5|3.64963503649635|4|4.166666666666666|25|4.9603174603174605|
|Fundamentals of programming|7|6.306306306306306|7|4.605263157894736|3|2.18978102189781|6|6.25|19|3.7698412698412698|
|Programming technologies|5|4.504504504504505|4|2.631578947368421|9|6.569343065693431|5|5.208333333333334|32|6.349206349206349|
|Algorithms 1|3|2.7027027027027026|8|5.263157894736842|7|5.109489051094891|2|2.083333333333333|30|5.952380952380952|
|Algorithms 2|7|6.306306306306306|11|7.236842105263158|9|6.569343065693431|5|5.208333333333334|35|6.944444444444445|
|Probability and Statistics|4|3.6036036036036037|7|4.605263157894736|5|3.64963503649635|3|3.125|34|6.746031746031746|
|English 1|5|4.504504504504505|9|5.921052631578947|3|2.18978102189781|5|5.208333333333334|24|4.761904761904762|
|English 2|7|6.306306306306306|5|3.289473684210526|10|7.2992700729927|6|6.25|22|4.365079365079365|
|Kazakh 1|7|6.306306306306306|9|5.921052631578947|11|8.02919708029197|9|9.375|27|5.357142857142857|
|Kazakh 2|4|3.6036036036036037|12|7.894736842105263|6|4.37956204379562|3|3.125|16|3.1746031746031744|
|Web technologies|0|0.0|4|2.631578947368421|11|8.02919708029197|6|6.25|25|4.9603174603174605|
|Database 1|7|6.306306306306306|8|5.263157894736842|7|5.109489051094891|2|2.083333333333333|25|4.9603174603174605|
|Database 2|9|8.108108108108109|10|6.578947368421052|11|8.02919708029197|6|6.25|22|4.365079365079365|
|Linear algebra|8|7.207207207207207|8|5.263157894736842|3|2.18978102189781|3|3.125|17|3.373015873015873|
|Discrete math|8|7.207207207207207|9|5.921052631578947|7|5.109489051094891|4|4.166666666666666|24|4.761904761904762|
|Physics|4|3.6036036036036037|9|5.921052631578947|6|4.37956204379562|9|9.375|22|4.365079365079365|
|Turkish 1|6|5.405405405405405|6|3.9473684210526314|9|6.569343065693431|10|10.416666666666668|30|5.952380952380952|
|Turkish 2|6|5.405405405405405|4|2.631578947368421|4|2.9197080291970803|2|2.083333333333333|26|5.158730158730158|
|Programming abstractions|6|5.405405405405405|7|4.605263157894736|6|4.37956204379562|5|5.208333333333334|23|4.563492063492063|


**P03.C** Write query that will show each rental and its genre, and show name of movie that was rent after that.