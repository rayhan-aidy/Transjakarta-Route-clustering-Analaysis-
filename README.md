---

# TransJakarta Route Clustering Analysis

## Project Overview
TransJakarta, a bus rapid transit system that has been operating since 2004, aims to reduce air pollution by offering a cleaner and more efficient alternative to traditional transportation methods. Despite its environmental benefits and extensive urban coverage, TransJakarta faces challenges in optimizing fleet and route utilization. One of the main issues is the high level of air pollution in Jakarta.

According to the official website of the Ministry of Environment and Forestry and UNEP reports, approximately 6.5 million people die annually due to poor air quality, with 70% of these deaths occurring in the Asia-Pacific region, including Indonesia, specifically in Jakarta. Urban transportation is identified as a major contributor to pollution, with vehicle emissions accounting for 70% of pollutants such as Nitrogen Oxides (NOx), Carbon Monoxide (CO), Sulfur Dioxide (SO2), and Particulate Matter (PM) (KHLK, 2021).

In this context, this project aims to analyze user travel data to understand the usage behavior of the TransJakarta public transportation system and find ways to optimize fleet and route utilization. By using clustering analysis on the travel data, we aim to identify the most frequently traveled routes and promote them to ultimately reduce air pollution in Jakarta.

## Business Understanding
The following are the features included in the dataset:

1. **transID**: Transaction ID
2. **payCardID**: Payment Card ID
3. **payCardBank**: Issuing Bank of the Payment Card
4. **payCardName**: Name on the Payment Card
5. **payCardSex**: Gender of the Cardholder
6. **payCardBirthDate**: Birth Date of the Cardholder
7. **corridorID**: Corridor ID
8. **corridorName**: Corridor Name
9. **direction**: Direction of Travel
10. **tapInStops**: Tap-In Stop ID
11. **tapInStopsName**: Tap-In Stop Name
12. **tapInStopsLat**: Tap-In Stop Latitude
13. **tapInStopsLon**: Tap-In Stop Longitude
14. **stopStartSeq**: Sequence Number of the Start Stop
15. **tapInTime**: Tap-In Time
16. **tapOutStops**: Tap-Out Stop ID
17. **tapOutStopsName**: Tap-Out Stop Name
18. **tapOutStopsLat**: Tap-Out Stop Latitude
19. **tapOutStopsLon**: Tap-Out Stop Longitude
20. **stopEndSeq**: Sequence Number of the End Stop
21. **tapOutTime**: Tap-Out Time
22. **payAmount**: Payment Amount

## Clustering Methodology
We will utilize various clustering algorithms to group the routes:
- **K-Means Clustering**
- **RECENCY, FREQUENCY, & MONETARY SEGMENTATION**


## Results
The output will include:
- A CSV file with the cluster labels assigned to each route.
- Visualizations of the clusters using PCA (Principal Component Analysis) and t-SNE (t-distributed Stochastic Neighbor Embedding).
- Summary statistics and insights for each cluster.

## Contributing

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact
If you have any questions or feedback, feel free to reach out:
- Email: rayhanaidy03@gmail.com


---
