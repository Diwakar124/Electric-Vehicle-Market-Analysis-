

# Electric Vehicle (EV) Market Analysis - India

This project is a data science-based analysis of the used car market in India, with a focus on identifying meaningful segments, price patterns, and market insights. It utilizes clustering algorithms (KMeans), PCA for dimensionality reduction, and insightful visualizations to provide actionable recommendations for the growing electric and used vehicle ecosystem.

## Project Summary

* **Domain**: Automotive, Market Analytics, Machine Learning
* **Techniques Used**: Clustering (KMeans), PCA, EDA, Data Visualization
* **Team**: Diwakar Kumar, Doordarshita Purohit
* **Dataset**: 8,128 used car listings with features like price, year, fuel type, KM driven, ownership, etc.
* **Dataset Link**: [Google Drive](https://drive.google.com/file/d/1yeTKNvAxCALz4QIKluGZqDFc6GbHt9dV/view?usp=sharing)

##  Objectives

* Identify key clusters in the used car market
* Analyze trends based on fuel type, ownership, transmission, and pricing
* Extract actionable business insights for car dealerships and online platforms
* Recommend future enhancements including EV integration

##  Methodology

1. **Data Cleaning**

   * Removed nulls in `mileage`, `engine`, `max_power`, `torque`, and `seats`

2. **Feature Selection & Scaling**

   * Selected: `year`, `selling_price`, `km_driven`, `seats`
   * Scaled using `StandardScaler`

3. **Clustering**

   * KMeans with optimal `k=3` determined via Silhouette Score
   * Clusters represent:

     * Cluster 0: Newer, premium vehicles
     * Cluster 1: Mid-aged, balanced price
     * Cluster 2: Older, budget vehicles

4. **Dimensionality Reduction**

   * Applied PCA for 2D visualization

5. **Visualization**

   * Cluster-wise insights using bar graphs
   * Analysis by fuel type, transmission, ownership

##  Key Findings

* **Petrol and Diesel** dominate the market; **CNG** shows niche eco-conscious adoption
* **Manual transmission** still leads, though **automatic** is growing in metro cities
* **First-owner cars** hold higher resale value and preference
* **Selling price is inversely related to KM driven**
* **Cluster analysis** helps in categorizing listings for pricing and marketing

##  Recommendations

* Integrate **EV tags** to monitor electric vehicle trends
* Apply **NLP** to extract model/manufacturer insights
* Add **Geo-tagging** for region-wise preferences
* Conduct **Sentiment analysis** on user reviews
* Build **prediction models** for price or quality segmentation

## Technologies Used

* Python (Pandas, Matplotlib, Seaborn, Sklearn)
* Jupyter Notebook
* Clustering (KMeans), PCA
* Data Visualization

## Future Work

This project can be enhanced with:

* Real-time EV market integration
* Deployment on dashboards (e.g., PowerBI, Streamlit)
* Predictive modeling for dynamic pricing

##  License
This project is open-source and available under the MIT License.
This project is open-source and available under the [MIT License](LICENSE).

---

Let me know if you want a sample folder structure or a link preview for hosting!
