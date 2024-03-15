- Neural Network model in tensorflow that utilizes binary logistic regression in order to predict a cancer diagnosis
  
- Data is made of of properties of a cellular nucleus such as:
  
  - radius (mean of distances from center to points on the perimeter)
  - texture (standard deviation of gray-scale values)
  - perimeter
  - area
  - smoothness (local variation in radius lengths)
  - compactness (perimeter^2 / area - 1.0)
  - concavity (severity of concave portions of the contour)
  - concave points (number of concave portions of the contour)
  - symmetry
  - fractal dimension (coastline approximation - 1)

- Diagnosis:
  - (M) Malignant - 1
  - (B) Benign - 0

- Predicts with about a 98% accuracy

- Dataset found at https://www.ybifoundation.org
- Inspiration article: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7472205/
