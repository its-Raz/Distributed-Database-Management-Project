<h1 align='center' style="text-align:center; font-weight:bold; font-size:2.5em"> Distributed Database Management Project</h1>

<p align='center' style="text-align:center;font-size:1em;">
  


</p>





# Contents

- [Part-1](#Part-1)
- [Part-2](#Part-2)


# Part-1
***Introduction***

- Part 1.1: media company, aiming to enhance viewer experience through data-driven insights, seeks assistance in detecting malicious records inserted by a rival media association.
Leveraging the power of Spark for big data processing, this project entails loading, analyzing, and detecting spam within the extensive "Daily Program Data" repository.
Six conditions are meticulously assessed per record to identify and mitigate the impact of malicious entries, ensuring data integrity and optimal viewer satisfaction.
- Part 1.2: In addition to detecting malicious records, the media company seeks assistance in organizing its data for efficient access across its distributed network. This entails determining genre popularity within each DMA and prioritizing genres based on DMA wealth scores. This part aims to optimize data placement and access to accommodate varying DMA resources.

The data in this part divided into 4 data sets, you can inspect the full scheme [HERE](https://github.com/its-Raz/Distributed-Database-Management-Project/blob/5e9a1412f78af7f5cb767484006534430bbc52bc/Part%201%20docs/PART%201%20DATA%20SET%20SCHEME.pdf)

You can also inspect the full requierments for it [HERE](https://github.com/its-Raz/Distributed-Database-Management-Project/blob/main/Part%201%20docs/PART%201%20REQUIERMENTS.pdf)

***Part 1.1 - Spam Detection***
- Extract and Transform: Utilizing Spark, load and preprocess data, applying necessary transformations. 
- Computation and Detection: Identify malicious records based on specified conditions and save them to CSV. The top 150 malicious entries should be displayed in ascending lexicographic order of the program code.

***Part 1.2 - Design and Deployment***
- Analyze program viewing data to rank genres by popularity within each DMA.
- Calculate DMA wealth scores based on net worth and income, then prioritize genre selection accordingly.
