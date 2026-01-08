# Prime-PX-Project
Build AI Project Course 
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
Where does your data come from? Do you collect it yourself or do you use data collected by someone else?
If you need to use links, here's an example:
[Twitter API](https://developer.twitter.com/en/docs)

| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       | 
| Paragraph   | Text        |
Limitations

Market fluctuations:
The model predicts prices based on historical data. Sudden changes in the real estate market (e.g., economic downturns, policy changes, seasonal demand) are not captured by the model.

Unique property characteristics:
Features like architectural style, interior quality, or scenic views may significantly influence a cabin’s price but may not be included in the dataset. The AI cannot fully account for these subjective factors.

Legal or zoning issues:
The AI does not assess legal aspects such as property rights, land use restrictions, or pending regulations, which can affect real prices.

Decision-making responsibility:
The predicted price is advisory, not binding. Users may still need human appraisers or real estate experts for final decisions.

Data quality limitations:
Incomplete, outdated, or biased datasets can lead to inaccurate predictions. The AI’s performance is directly dependent on the quality and quantity of the training data.
How the project could grow

Expand the dataset:
Collect cabin sales data from multiple regions and countries to make predictions more generalizable. Include additional features like property age, renovations, energy efficiency, proximity to amenities, or scenic views.

Improve model complexity and accuracy:

Experiment with deeper neural networks or ensemble models to capture more complex patterns in cabin pricing.

Incorporate geospatial data (GIS) to account for location-based price trends.

Develop user-friendly applications:

Create a web or mobile app where buyers and sellers can input cabin features and receive price predictions instantly.

Add visualizations like charts and maps to make predictions more intuitive.

Predict market trends:
Extend the model to forecast future price trends, not just current estimates, helping users plan buying or selling strategies.
