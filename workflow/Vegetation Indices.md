Vegetation Index Computation and Crop Health Analysis

Overview

Vegetation indices were computed from the preprocessed multispectral imagery to monitor crop health and detect stress conditions in paddy fields. These indices leverage the spectral response of plants in the visible and near-infrared regions.

Healthy vegetation strongly reflects NIR and absorbs red light, which makes vegetation indices effective for early stress detection.

Step 1: False Color Composite

A false color composite was generated using the NIR, Red, and Green bands. This visualization highlights vegetation and allows rapid visual inspection of crop conditions.

Applications:

Identification of stressed zones

Field boundary detection

Spatial variability analysis

4
Step 2: Normalized Difference Vegetation Index (NDVI)

NDVI was computed using the formula:

NDVI = (NIR - Red) / (NIR + Red)

NDVI values indicate vegetation health:

High values → healthy crops

Low values → stressed or damaged vegetation

NDVI was used to:

Monitor crop vigor

Identify unhealthy regions

Support agricultural decision-making

Step 3: Soil Adjusted Vegetation Index (SAVI)

SAVI was calculated to reduce the influence of soil brightness in areas with sparse vegetation.

SAVI formula:

SAVI = ((NIR - Red) / (NIR + Red + L)) × (1 + L)

Where L is the soil adjustment factor.

SAVI is useful for:

Early crop stages

Sparse vegetation

Soil background correction

4
Step 4: Spatial Analysis and Crop Health Mapping

The computed vegetation indices were analyzed to identify spatial variations in crop health. Areas with lower index values were marked as potential stress zones.

This step enabled:

Targeted intervention

Precision farming

Efficient resource utilization

Step 5: Interpretation and Insights

The results showed variability in crop health across the study region. These insights can help farmers and agricultural agencies:

Monitor crop growth

Detect disease early

Improve yield prediction

Optimize irrigation and fertilizer usage

Summary

Vegetation indices derived from multispectral imagery provide a powerful tool for precision agriculture. These indices allow early detection of stress and enable data-driven agricultural management.