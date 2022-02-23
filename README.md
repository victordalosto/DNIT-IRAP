# DNIT-IRAP
This program was used at the National Department of Infrastructure and Transport of Brazil - [DNIT](https://www.gov.br/dnit/) as part of the iRAP (International Road Assessment Programme) codification.

## iRAP
The [iRAP](https://irap.org/) is a registered charity dedicated to saving lives by eliminating high-risk roads around the world. Like many life-saving charities working in public health, it uses a robust, evidence-based approach to prevent unnecessary death and suffering.

The iRAP codification is being implemented in Brazil (2021-2022) by monitoring its Federal road network, composed of approximately 62000 km.

The methodology works by inspecting highways with high accident rates, analyzing and classifying each highway in stars (Star Rating), which provides a simple and objective measure of the road safety level for vehicle occupants, motorcyclists, cyclists and pedestrians. The analysis results are used to propose engineering solutions through investment plans (Safer Roads Investment Plans).

## Program
This program was used to provide the product used as input in the iRAP codification. Its use allowed the extraction of more than 3.1 million georeferenced roads images to be evaluated.

The program works by accessing the internal DNIT Network, extracting over 75 million images from the [Continuous visual monitoring videos](https://github.com/victordalosto/DNIT-LVC), filtering the images based on its odometer and iRAP spacing, georeferencing each image localization using a Log.XML, condensing all information in an Excel Input, and rearranging all the files in a specific structure for each Brazilian Federal Road (2500+ folders).

After all integrity and consistency check was done in all the DATA, the files were stored in HDs to be transported to the iRAP's codification engineers team.
