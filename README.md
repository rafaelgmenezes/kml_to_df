# kml_to_df
Python function to transform google earth .kml files list into a pandas DataFrame \n
    \tDataFrame content: 
        Filename -> the .kml filename 
        Lon      -> meridians coordinate
        Lat      -> parallels coordinate
    output options: 
        fmt = 'df'   -> a DataFrame object  (default)
        fmt = 'csv'  -> save DataFrame in a .csv file
        fmt = 'both' -> both above outputs
    .kml files location:
        'kmlfiles' folder into the current working directory
        or directly in the current working directory
