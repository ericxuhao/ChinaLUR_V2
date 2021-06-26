# ChinaLUR-V2.0
National predictions of NO2 and PM2.5 based on Land Use Regression, satellite data and Universal Kriging--version2.0    
**Format**：Geotiff      
**Spatial Resolution:** 1km×1km     
**Temporal Resolution:** Annual average      
**Time coverage:** 2013~2017     
**Pollutants:** NO2,PM2.5      
**Units:** Concentrations for both pollutants (NO2, PM2.5) are in units of μg/m3        
**Map size:** 4835×4044        
**Projection:** China_Albers_Equal_Area_Conic(datum:WGS84)     
**proj4 code:** +proj=aea +lat_1=25 +lat_2=47 +lat_0=0 +lon_0=105 +x_0=0 +y_0=0 +datum=WGS84 +units=m +no_defs     
**HOW TO OPEN/READ THE FILE:** Using ArcGIS or any programming language with GDAL package (e.g. python+gdal/R+rgdal)    
**Data creator:** Hao Xu      
**Author:**  Hao Xu, Matthew Bechle and Julian Marshall     
**Contact:** Hao Xu (xuhao13@tsinghua.org.cn / xuhao13@uw.edu)     
**PLEASE email Hao Xu to ask for the passcode of these files**     
**These data must not be used for publications before authorized. 
**!!All the 7z files should be downloaded before decompress them!!**                   
**If you use these data, please cite them as:**
Xu, H., Bechle, M.J., Wang, M., Szpiro, A.A., Vedal, S., Bai, Y., Marshall, J.D., 2019. National PM2. 5 and NO2 exposure models for China based on land use regression, satellite measurements, and universal kriging. Sci. Total Environ. 655, 423-433. https://doi.org/10.1016/j.scitotenv.2018.11.125

**Performance of PM2.5 models(10-fold CV)**                     
year  R2	RMSE RPE                    
2013	0.92	6.58	9.65%                
2014	0.90	6.46	10.5%                 
2015	0.89	6.06	11.6%              
2016	0.88	5.91	12.3%           
2017	0.87	5.60	12.1%              
**Performance of NO2 models(10-fold CV)**                     
year  R2	RMSE RPE                
2013	0.69 	7.08 	16.9%               
2014	0.73 	6.66 	17.6%               
2015	0.77 	5.97 	18.8%                     
2016	0.78 	5.72 	17.9%                    
2017	0.80 	5.52 	16.6%

