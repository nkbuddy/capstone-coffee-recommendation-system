# capstone-coffee-recommendation
## Project Scope
We’ve reached peak coffee culture in America. While your local coffee shop is perfect for a mid-afternoon pick-me-up, the very best coffee in America is definitely worth traveling for. With plenty of brunch spots and bakeries to get your morning fix, we’re after the slow, loving pour-overs, the iconic America coffee houses and those that do something absolutely extraordinary with their joe.
## Procedure and Project Overview

1.collecting the data<br>
  Data Sources: coffeereview.com<br>
  web scraping 1000+ coffee review in north america<br>
  
2.Data cleaning and EDA<br>
  -How were the missing values treated?<br>
  Price per ounces:<br>
  It has a lot of missing values, different currency, and units.<br>
3.using Linear Regression to study the correlation between price and coffee score<br>
4.using NLP analysis what is the coffee taste like<br>
<img src="images/COFFEE_WHEEL.PNG" width="500" height="500">
## Results
<img src="images/readme_corr.PNG" width="500" height="500">
the hishest correlate to 
<img src="images/readme_nlp.PNG" width="500" height="500">
<img src="images/readme_score.PNG" width="500" height="500">
<img src="images/readme_ols_model.PNG" width="500" height="500">
## Next Step
Finally, a few things were not considered when building the engine and they should deserve some attention:<br>
<li>
The washing technique and roaster location of the coffee was not checked. In fact, this could be important to affect coffee quality.<br>
<li>
another point concerns the replacement of the keywords. In some cases, it was shown that the flavor had a different meaning than the original word(green tea flavor breaks down to green and tea flavor). Only 67 flavors were defined.<br>
<li>
The gap between review date and roasted date. The longer the coffee sits inside the package, the quality becomes wost.<br>

Next step would be creating a SVD model to let people rate the coffee bean and genarate a new recommandation base on the score.
