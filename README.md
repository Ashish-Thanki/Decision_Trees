# Decision_Trees

Tutorials and Functions which contain relevant information on Decision Trees. The tutorials go through the Iris dataset and the moons dataset. 

The Iris dataset tutorial explains and gives watch-its on how to use and apply Decision Trees with GridSearch. 

The moons datatset tutorial shows how to search for the right parameters for a DecisionTreeClassifier. Using the best parameters obtained we can use this on smaller batches. The tutorial then shows how to make a RandomForestClassifier without actually using the class in Sk-Learn - great way to understand what is going on under the hood!

NOTE: There is an error within the moons dataset with the accuracy scores stated within the markdowns compared to that shown as an output. I have kept this in to show you the difference between what I achieved whilst writing the document compared to what the final output result was when re-run the entire programme. The lesson here is the marginal gain (could have been a marginal loss too) within the accuracy score. Due to the random nature of the shuffling process across the entire workbook, we may obtain different values every time we run the programme (even though I used random_state=42 where I thought I could - let me know if you see somewhere I have!)

