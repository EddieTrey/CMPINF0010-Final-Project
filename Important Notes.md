## Important Notes for Running on Win 10

#### If an error occurs when pip installing geopandas - Microsoft Visual C++ 14.0 required  
- https://stackoverflow.com/questions/64261546/how-to-solve-error-microsoft-visual-c-14-0-or-greater-is-required-when-inst
- Install Visual Studio Build Tools 2019 from Microsoft  
#### If further errors - Command "python setup.py egg_info" failed with error code 1
- https://stackoverflow.com/questions/54734667/error-installing-geopandas-a-gdal-api-version-must-be-specified-in-anaconda
- In Order: 
- pip install wheel
- pip install pipwin
- pipwin install gdal
- pipwin install fiona
- pip install geopandas  
pipwin is a complementary tool for pip on Windows. pipwin installs unofficial python package binaries for windows provided by Christoph Gohlke. Some packages run better and faster
than official ones.