<h1 Align="Center">
  
  Movie ETL

  # Overview
  
  <p>For this project we were tasked with extracting, transforming, and then loading disparate data into a SQL database</p>
  
  ## Results
<p>We created a function that imported two CSVs and a JSON file into Pandas dataframes where they were then transformed by combining like for like columns and cleaning datatypes to be more usable. Finally two of the dataframes were exported to an SQL database. The code is heavily commented and explains the steps of the functions.</p>

  ## Potential Changes
 <p> Two issues became readily apparent during this process. A) the strategy used relied too much on nested functions, which made it exceptionally hard to debug. Much of the process would have been easier done in individual cells which would then let variables be able to checked midway through the process. B) There are no primary or secondary keys in the SQL database. Creating those key connections would make the process of working with the database easier. </p>
