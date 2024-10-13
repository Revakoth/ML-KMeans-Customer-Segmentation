# Customer Segmentation with K-means
Business Scenario
<br>
Segment our customers to help the marketing department in a FMCG (Fast-Moving Consumer Goods) company to launch new products and sales based on the segmentation. Therefore we will save our time and money by marketing a specific group of customers with selected products.
<br>
Data has been collected through the loyalty cards they use at checkout.
<br>
We will utilize K-Means and PCA algorithms for this project and see how we define new grouped customers!

## Data!

#### Data Dictionary:
<ul>
  <li>ID: Shows a unique identification of a customer.</li>
  <li>Sex: Biological sex (gender) of a customer. In this dataset, there are only 2 different options.
    <ul><li>0: male</li><li>1: female</li>
    </ul>
  </li>

  <li>Marital status: Marital status of a customer.
    <ul><li>0: single</li><li>1: non-single (divorced / separated / married / widowed)</li>
    </ul>
  </li>

 <li>Age: The age of the customer in years, calculated as current year minus the year of birth of the customer at the time of the creation of the dataset
    <ul><li>18 Min value (the lowest age observed in the dataset)</li><li>76 Max value (the highest age observed in the dataset)</li>
    </ul>
  </li>

<li>Education: Level of education of the customer.
    <ul><li>0:other / unknown</li><li>1: high school</li>
      <li>2: university</li><li>3: graduate school</li>
    </ul>
</li>

<li>Income: Self-reported annual income in US dollars of the customer.
    <ul><li>35832 Min value (the lowest income observed in the dataset)</li><li>309364 Max value (the highest income observed in the dataset)</li>
    </ul>
  </li>

  <li>Occupation: Category of occupation of the customer.
    <ul><li>0: unemployed/unskilled</li>
      <li>1: skilled employee / official</li>
       <li>2: management / self-employed / highly qualified employee / officer</li>
    </ul>
  </li>
  
<li>Settlement size: The size of the city that the customer lives in.
    <ul><li>0: small city</li>
      <li>1: mid-sized city</li>
       <li>2: big city</li>
    </ul>
  </li>
</ul>

## Conclusion
With K-means clustering and PCA, We segmented our customers into 4 groups.
The four groups are:
<ul>
  <li>Young and Standard </li>
  <li>Old and Rich </li>
  <li>MiddleAge and Fewer opportunities</li>
  <li>MiddleAge and Career Focused</li>
</ul>
We are ready to start to choose our groups based on our aims and marketing them!
Segmentation helps marketers to be more efficient in terms of time, money and other resources.

They gain a better understanding of customer's needs and wants and therefore can tailor campaigns to customer segments most likely to purchase products.
