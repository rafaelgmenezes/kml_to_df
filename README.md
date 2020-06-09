# kml_to_df
Python function to transform google earth .kml files list into a pandas DataFrame 
    DataFrame content: 
        Filename -> the .kml filename 
        Lon      -> meridians coordinate
        Lat      -> parallels coordinate
    output options: 
        fmt = 'df'   -> a DataFrame object  (default)
        fmt = 'csv'  -> save DataFrame in a .csv file
        fmt = 'both' -> both outputs options above
    .kml files location:
        folder in current working directory
        or files directly in current working directory
