# Siga_SaltSugarFat
Considering amount of salt, sugar, and fat in processed and ultra-processed foods (NOVA) guided by Siga classification system 

**Source for Siga**
The guidelines for dividing UPF and UMPF (NOVA) by amount of Sugar, Salt, and Fat comes from: Davidou, Sylvie & Christodoulou, Aris & Fardet, Anthony & Frank, Kelly. (2020). The holistico-reductionist Siga classification according to degree of food processing: An evaluation of ultra-processed foods in French supermarkets. Food & Function. 10.1039/C9FO02271F. 
This code does not account for any other processing or additives -- this is just for the salt, sugar, and fat cutpoints

**NDSR Data**
3 csvs needed for this
1) The wide dataframe from NDSR files 4 and 9 
2) The long dataframe that comes from the NDSR file 1 (food and ingredient list).  Need to already have NOVA score
3) One of the NDSR codebooks has the USDA codes. Create a csv with only two columns: USDA code and FoodName (make sure the column is called "FoodName"--change it if it is not)
