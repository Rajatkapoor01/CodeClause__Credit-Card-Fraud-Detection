**Bank card fraud detection using machine learning<br>**
A web application for analyzing bank transactions and detecting fraud.
**Main functions:**
data set preparation,
use of machine learning algorithms,
report with graphs, tables and transaction analysis,
comparison of the operation and accuracy of the three algorithms,
manual transaction verification.
<br>
<br>
**Technologies used**
Python v3+
Pandas, numpy, matplotlib, seaborn, sklearn
Streamlit
Dataset
The project uses a free set of data from free access, which includes a collection of credit card transactions, both legitimate and fraudulent. The data set serves as the basis for training and evaluating the fraud detection model. We took the data set from the website kaggle.com. This site is an online resource and community for data science, machine learning and data research specialists.
<br>

**SCREEN SHORT**
![ScreenShort 1](https://github.com/Rajatkapoor01/CodeClause__Credit-Card-Fraud-Detection/blob/main/SShort/SS1.png)
![ScreenShort 2](https://github.com/Rajatkapoor01/CodeClause__Credit-Card-Fraud-Detection/blob/main/SShort/SS2.png)
![ScreenShort 3](https://github.com/Rajatkapoor01/CodeClause__Credit-Card-Fraud-Detection/blob/main/SShort/SS3.png)
![ScreenShort 4](https://github.com/Rajatkapoor01/CodeClause__Credit-Card-Fraud-Detection/blob/main/SShort/SS4.png)
![ScreenShort 5](https://github.com/Rajatkapoor01/CodeClause__Credit-Card-Fraud-Detection/blob/main/SShort/SS5.png)
![ScreenShort 6](https://github.com/Rajatkapoor01/CodeClause__Credit-Card-Fraud-Detection/blob/main/SShort/SS6.png)

**How to run**
Download project

Open in code editor

Install or update pandas, numpy, matplotlib, seaborn, sklearn via terminal.

I use pip. Example:

pip install -U scikit-learn
See the current commands on the Internet for the query "how to install pandas/numpy/...".

Install streamlit:

pip install streamlit
Run project:

streamlit run main.py

<br>

**How to use "manual transaction verification"?**
You have 3 csv files. The creditcard.csv file contains all transactions. In the other two files, transactions are divided into fraudulent and legal ones.

Open any csv file
Copy any line. For example: -1.1152878574425795,-19.1397328634111,9.28684735978866,-20.134992104854,7.81867331002574,-15.652207677206302,-1.66834770694329,-21.3404780994803,0.6418997011947,-8.55011032700099,-16.6496281595399,4.81815244707108,-9.44531478308794,1.3170562933234098,-7.24346097400378,0.830910291033798,-9.533257050393189,-18.750641147467398,-8.09264877340557,3.32675827497024,0.42720343146936,-2.1826919456095504,0.5205430723666421,-0.7605564151887328,0.6627666383972359,-0.948454306235033,0.12179592582979301,-3.3818429293561,-1.2565236213625801,0.20610286556509647,1
Delete ",1" or ",0" in the end.
Paste new line in input label and submit. For example: -1.1152878574425795,-19.1397328634111,9.28684735978866,-20.134992104854,7.81867331002574,-15.652207677206302,-1.66834770694329,-21.3404780994803,0.6418997011947,-8.55011032700099,-16.6496281595399,4.81815244707108,-9.44531478308794,1.3170562933234098,-7.24346097400378,0.830910291033798,-9.533257050393189,-18.750641147467398,-8.09264877340557,3.32675827497024,0.42720343146936,-2.1826919456095504,0.5205430723666421,-0.7605564151887328,0.6627666383972359,-0.948454306235033,0.12179592582979301,-3.3818429293561,-1.2565236213625801,0.20610286556509647 (At the end of the new line, I deleted ",1")
<br>

