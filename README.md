# LTS-disaggregation
A group of functions specifically designed to disaggregate the South African Land Type Survey (LTS) into soil maps based on the DSMART algorithm developed by Odgers et al., (2014). These codes follow a two step disaggregation method by stratifying the LTS with landform elements and then disaggregating. Disaggregation can be implemented with any classification algoirthm in the caret package and therefore, parameters can be optimised. The codes can also be used on soil legacy data that does not require this two-step approach. 

Provides code to:
  i) Quantitatively select landform elements (in progress)
  ii) Overlay landform elements with LTS polygons
  iii) Check and correct common geometric errors when polygonising and overlaying landform elements with the LTS
  iv) Feature selection (in progress)
  v) Modified code from the DSMART algorithm (Odgers et al., 2014) to incorporate the caret package
  vi) Code to disaggregate each LTS polygon seperately (in progress)



