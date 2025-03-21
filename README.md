# Crowdfunding_ETL
Project 2 

# Crowdfounding_info_df
Using crowdfounding.xlsx we created crowdfounding_info_df to show a overview of crowdfounding.xlsx.
![image](https://github.com/user-attachments/assets/a583fed2-0282-4fbd-bb51-f656f0fcdcfb)

# Category and Subcategory DataFrames
From crowdfounding_info_df we split the category & sub-category column and created both category_df and subcategory_df dateframes. 
![image](https://github.com/user-attachments/assets/d38d7bcd-be51-406e-8255-0ddd638ec762) ![image](https://github.com/user-attachments/assets/b853ef6f-b67f-491f-b984-c10de816a53a)


Exported both dataframes to a csv.

# Campaign DataFrame
Using crowdfounding.xlsx we created campaign_cleaned dataframe with columns cf_id, contact_id, company_name, blurb, goal, pledged, outcome, backers_count, country, currency, launched_at, deadline, category_id, and subcategory_id
![image](https://github.com/user-attachments/assets/b37f1798-99cf-4308-84aa-f941a25797d9)


Exported dataframe to a csv.

#  Contacts DataFrame
Using contacts.xlsx we created Contact_info
![image](https://github.com/user-attachments/assets/9d955640-4187-475e-83dc-e3eeb31bf38a)


Exported dataframe to a csv.

# QuickDBD
useing QuickDBD web app we made a ERD diagram to show relationship between are exported csv file.
![image](https://github.com/user-attachments/assets/1ac54ce0-f279-4be4-882c-44ae91ef091a)


from here we exported the diagram and named it crowdfounding_db.sgl, then using pgAdmin4 we created our schemas. 

<ins>Sources:</ins>
QuickDBD https://www.quickdatabasediagrams.com/
Pandas https://pandas.pydata.org/
pgAdmin https://www.pgadmin.org/

<ins>Group Members:</ins>
Tomas Banuelos,
Cole Sherwin,
Robert Lawrence,
Andrew Njogu, and
Noah Stevenson
