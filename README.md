# kml_to_df
Developed with Python 3.7.6

README:
    Python function to transform google earth .kml files list into a pandas DataFrame. 
    Necessary function for the 'Mapping_kml' code (https://github.com/rafaelgmenezes/Mapping_kml).
    
    .kml files location:
        folder in current working directory
        or files directly in current working directory
    
    dataFrame ouput content: 
        Filename -> the .kml filename 
        Lon      -> meridians coordinate
        Lat      -> parallels coordinate
    output options: 
        fmt = 'df'   -> a DataFrame object  (default)
        fmt = 'csv'  -> save DataFrame in a .csv file
        fmt = 'both' -> both outputs options above
