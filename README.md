# Data Cleaning :

Find out if any column have null values.

Used pivot_table to get Item_Identifier wise Item_Weight
Calculated mean for each Item_Identifier and fill it in null value to respective Item_Weight

Identify 2410 null values of Outlet_Size
Find out which Outlet_Type has missing values
Filled mode of each Outlet_Size of respective Outlet_Type

Identify 526 "0" values in Item_Visibility and filled with mean value

Corrected typing error in Item_Fat_Content 
eg. Converted LF, low fat to Low Fat and reg to Regular

Added new column as  New_Item_Type by getting first 2 charecter of Item_Identifier
like FD, NC and DR and give them name as Food, Non-Consumable and Drinks respectively
using grouby(), we find out Non-Consumable type is mapped to Low Fat category in Item_Content_Type, so marked it as Non-Edible in Item_Fat_Content column

Calculated total years of establishment


# Insights :

Count_of_Item_fat_content

![Count_of_Item_fat_content](https://github.com/user-attachments/assets/6b55fd29-432c-4d9e-a03a-7f0d4edcfc9c)

Count_of_Item_Type

![Count_of_Item_Type](https://github.com/user-attachments/assets/68cb49da-a81a-49db-b4fb-9e63d9db34ea)

Count_of_Outlet_Establishment_Year

![Count_of_Outlet_Establishment_Year](https://github.com/user-attachments/assets/fd0a78c8-be88-4bb3-ac9d-b709636f07b3)

Count_of_outlet_location_type

![Count_of_outlet_location_type](https://github.com/user-attachments/assets/a0e20553-14cc-4813-bc10-f3a391ded881)

Count_of_outlet_size

![Count_of_outlet_size](https://github.com/user-attachments/assets/fa7080f8-3cf4-4ac1-9f0e-d525b5c61939)

Count_of_outlet_type

![Count_of_outlet_type](https://github.com/user-attachments/assets/af38993c-1574-44c2-9ef1-568e42a428bb)

Distribution_of_Item_Weight
![Distribution_of_Item_Weight](https://github.com/user-attachments/assets/09c14658-d49f-4d82-95ce-adfeaa28c901)
