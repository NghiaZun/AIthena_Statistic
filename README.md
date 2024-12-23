# This repository provides an overview and evaluation of the performance statistics.

## Performance Statistic

The Excel file contains statistical data related to query performance. Below is a breakdown of the key columns and their descriptions:

1. **Query Name**: Names of the queries, e.g., `query-p2-1-kis`, `query-p2-2-kis`.
2. **Query Description**: Detailed textual descriptions of the queries, specifying the scene or content being queried.
3. **Query Results**: Information about the retrieved results, such as video IDs and their positions in the dataset.
4. **Performance Metrics**:
   - **R1**: Number of result at rank 1.
   - **R5**: Number of results in the rank range [2, 5].
   - **R10**: Number of results in the rank range [6, 10].
   - **R20**: Number of results in the rank range [11, 20].
   - **R50**: Number of results in the rank range [21, 50].
   - **R100**: Number of results in the rank range [51, 100].
     
## Achieved rank 1 in 3rd preliminary round
![achieve](images/Rank_1_in_3rd_preliminary_round.png)

## Function experiments

### Full graphical user interface and simple query test
![Graphical User Interface](images/UI.drawio.png)
### OCR-based query
![OCR-based query](images/OCR.jpg)
### Question and Anwser using GPT-4o API
![Question and Anwser](images/QA_Test.png)
### Rank comparison of CLIP-based and Gen-AI image-based query
![Compare 1](images/MedalCLIP.png)
![Compare 2](images/medalgenAI.png)





    
