# DataCO-Data-Cleaning-and-Processing
Business Analytical pacmann project, dataco supply chain optimization
Dataset Explanation
The dataset used in this project are DataCo’s Supply Chain dataset that provide by the Pacmann Academy. The dataset has 52 columns, its descriptions is in the sheet “Description” of the dataset. In this project only 13 columns are used which are related to the objectives, those are:

![18 dataset used deskripsi](https://github.com/indra2878/DataCO-Data-Cleaning-and-Processing/assets/129472057/920acfe4-cdb2-4ea3-b8f0-3ea0255ec4aa)

The data exploration process carried out includes: identification of missing values, duplicate data, outliers and inconsistent formats. (see the Jupiter Notebook file to see the complete data processing process and results).
Identify missing values. 

![04 data clean missing value info](https://github.com/indra2878/DataCO-Data-Cleaning-and-Processing/assets/129472057/3ad3adbb-86eb-4c6d-a5af-b7d7f4c94888)

From the dataset information, the number of non-null values is the same as the amount of data, so that there are no missing values in the dataset. Beside that we can see the data type of each columns already meet the expectation.

Identification of duplicate data

![04 cek duplicated](https://github.com/indra2878/DataCO-Data-Cleaning-and-Processing/assets/129472057/2dd7b772-ec1a-40f9-84b2-71bd4e097e01)

From the data frame above, there are null duplicated data, so that there are no duplicated data.
Identification of Inconsistent data
From the data information above data types of each columns are meet the expectation, “order date” and “shipping date”  are already set to datetime64(ns). So there is no need to change the data type anymore.
