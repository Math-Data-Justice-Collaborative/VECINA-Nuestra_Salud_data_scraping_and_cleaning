# VECINA-Nuestra_Salud_data_scraping_and_cleaning
This Jupyter notebook has the packages and codes for scraping the website Nuestra Salud directoria médico: https://www.nuestrasalud.com/directorio-medico. 

The package we're using to scrape data is BeautifulSoup, the documentation to use this program is here https://beautiful-soup-4.readthedocs.io/en/latest/. 

The main data set is Nuestra_Salud_directoria.csv and you will find the following columns in it:
* `Nombre`--The Doctor, nurse, or translators name
* `Grado` --The Doctor, nurse, or translators degree
* `Grado Dos` --The Doctor, nurse, or translators second degree if they have one
* `Especialidad` --The Doctor, nurse, or translators specialization in their field.
* `Hospital` -- Where the Doctor, nurse, or translators works
* `Dirección` --The address of the health center
* `Número de` --The second line of the address, if it exists.
* `Ciudad` --The city that this health center is located
* `Estado` --The state that this health center is location, either RI, MA, or CT.
* `Código Postal` --The zip code of this health center
* `Experto en` --A broad specialization category named by Nuestra Salud
* `Teléfono` --The health centers phone number
