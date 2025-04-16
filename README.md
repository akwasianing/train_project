For mileage column since only 2 out of 5847 rows have missing values, these two rows can be dropped. (negligible impact)

Since skewness values for the columns (Engine, Power, Seats) are positive, indicating right-skewed distributions, the missing values in these columns are replaced with their respective medians, as the median is robust to outliers and better suited for skewed data

New_Price column is dropped due to a high percentage of missing values (~86%). With such a significant portion of data missing, retaining the column would likely reduce the quality and interpretability of the analysis. Imputation would rather be unreliable and potentially introduce bias that is why the New_Price column is dropped.
