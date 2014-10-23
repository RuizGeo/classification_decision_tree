classification from Classification And Regression Tree (CART)
===============================
Classification by decision tree (CART) for use in processing framework QGIS

Input parameters

  vector samples: Vector to training model tree, the fields of the table shall be equal to Vector datas. Only with the class column more.
  
  Classes field: Field with values classes. Type data equal the integer.
  
  Vector datas: Vector to classfication
  
  Maximum depth: Depth of tree,more information in library Scikit-Learn model classification decision tree.
  
Observation: 
  Nominal data type must be converted to string if they are not.
  
