# Historical Cotton textiles data for Mexico, 1850–1933

This repository contains original data and one analytic dataset for the research article:

Razo, Armando and Stephen H. Haber (1998), [The Rate of Growth of Productivity in Mexico, 1850–1933: Evidence from the Cotton Textile Industry](https://doi.org/10.1017/S0022216X98005136). 
Journal of Latin American Studies , Volume 30 , Issue 3 , October 1998 , pp. 481 - 517

> Abstract
>
> This article employs previously unused data sources and techniques in order to estimate labour productivity and total factor productivity in the Mexican cotton textile industry over the period 1850–1933. Our findings indicate: (1) substantial productivity growth prior to the Porfiriato; (2) rapid productivity growth throughout the Porfiriato; (3) a swift, though incomplete, recovery from the Revolution during the 1920s; and, (4) an insignificant impact on productivity from the Great Depression. We also find evidence that the large, joint stock, limited liability firms that were founded during the Porfiriato had higher levels of total factor productivity than privately owned firms, but only for a short period of time, which suggests that these firms might have been sub-optimally large. Our results also indicate that labour markets in Porfirian Mexico were efficient. This suggests that manufacturers may not have had the monopsony power in labour markets that the literature indicates.

# Folders

## data

This folder includes the analytic panel dataset (prefix: MASTERMX) in two formats: an excel file (converted from original 123 spreadsheet) and a CSV text file.

A subfolder called "RAW data, 1837-1932" includes annual information used to build the main panel dataset.  Each spreadsheet lists its main source.  These annual sources might contain additional information not included in main dataset.

Please note that original data entry used Lotus 1-2-3 spreadsheets, so these "raw" data files are subsequent Excel data conversions.  If you import raw files into other programs (e.g., R Statistical Environment), please double check options for accurate format conversions (e.g., entries that might appear to be numbers could be encoded as strings, so you would need to recast these as numbers).

## docs

This folder includes three documents:

- "MasterMX.pdf" is a codebook for the main panel, including sources for historical information.

- "DataYear.pdf" offers a quick overview of available data per cross-section, ranging from 1837 to 1932

- "Deflator.pdf" describes price index adjustments


# Citation

If you use this dataset, please cite the original article along with this public dataset citation:

Razo, Armando and Stephen H. Haber (2021). Historical Cotton textiles data for Mexico, 1850–1933.  URL: https://github.com/arazoNet/MX-textiles-data. Access date: _____.

# License

Original data sources and research article have their own copyright licenses.

The analytic dataset uses the Academic Free License (AFL 3.0), which offers flexible licensing arrangements for derivate dataset artifacts.