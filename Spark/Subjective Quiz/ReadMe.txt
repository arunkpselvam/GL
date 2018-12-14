Dear Participant,

Please find below the Subjective Quiz for Big Data on Spark. Kindly make your submission before the deadline.

The data set refers to clients of a wholesale distributor. It includes the annual spending in monetary units (m.u.) on diverse product categories

The data set is available at https://archive.ics.uci.edu/ml/datasets/Wholesale+customers#.

Description of variables is as folllows:

1)  FRESH: annual spending (m.u.) on fresh products (Continuous);

2)  MILK: annual spending (m.u.) on milk products (Continuous);

3)  GROCERY: annual spending (m.u.)on grocery products (Continuous);

4)  FROZEN: annual spending (m.u.)on frozen products (Continuous)

5)  DETERGENTS_PAPER: annual spending (m.u.) on detergents and paper products (Continuous)

6)  DELICATESSEN: annual spending (m.u.)on and delicatessen products (Continuous);

7)  CHANNEL: customers Channel - Horeca (Hotel/Restaurant/Cafe) or Retail channel (Nominal)

8)  REGION: customers Region Lisnon, Oporto or Other (Nominal)

Our goal is to learn about DataFrame operations in Spark here.

The  dataset gives data about sales of 6 category of products across 3 regions via 2 channel. We would like to know if there are any differences in sales of any category across any region or via any channel. Let us do the following tasks:

Read the csv file as a dataframe. And, not as RDD. See the schema of the DF.
Use select to view a single column or a st of chosen columns.
Use filter to see records with fresh sales more than 50000 only.
Create aggregates on channels and regions variables.
Use describe to see summary statistics on dataframe.
Change datatype of Channels to Strings.
Instructions:

Total marks allotted for this quiz is 30 where 5 marks is alloted to each task.
Please submit both Jupyter notebook(.ipynb) file and html file along with output.