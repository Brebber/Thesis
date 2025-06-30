## US Air Data & Models
Much of this code is from the article by Lei et al. "Forecasting the evolution of fast-changing transportation networks using machine learning" (2022) and from the article by Kämper: "Predicting Delayed Trajectories Using Network Features: A Study on the Dutch Railway Network" <br/>
Original GitHub: https://github.com/amarallab/transportation_network_evolution/blob/master/README.md?plain=1 <br/>
Kämper GitHub: https://github.com/merelkaemper/MSc-Thesis-main <br/>
Only their data preparation code is used to implement the code I used for the Dutch Railways to the US Airways.

**Repository structure:** <br/>

* **data/** -- 
    * **raw_usair_data/** -- data folder to put raw US air transportation data (download at https://doi.org/10.21985/n2-9r77-p344)
    * **features/** -- data folder to put calculated topological features (running raw2features)
* **\models.ipynb** -- main complete notebook for the entire pipeline.


**Steps:** <br/>
* Download the raw US Air data from the Lei, et al. GitHub page. 
* Simply run **models.ipynb** in order. 
