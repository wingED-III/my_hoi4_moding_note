# Heart of Iron 4 modding note
<sub><sub><sub>
I am non native english speaker but I'm willing to improve.
<sub>
- Don't overwrite file. If you just want to add new things.<br>
  ~Don't  use a file name that is the same with original file.
    <p> example: Japan Ship name mods  
    <br>
    when create new file at "MOD_FOLDER_NAME"\common\units\names_ships\ 
    <br>
    Use name like: "MyMod"_ship_names
    <br>
    Not : JAP_ship_names 
    <br>
    <br> then in MyMod_ship_name write <br>
    	for_countries = { JAP } 
    <br>
    if you want to use with only japan.
    </p>
    <br>
- still not sure how the file work. It feel like the game read whatever in those folder regardless the tag name
    <p>example: MyMod_ship_name -work. It not neccessary to be like "COUNTRY TAG"_ship_name (i.e. JAP_ship_names)   </p>
    <br>
- the Uppercase code is likely to be used on some other files.
    <p>example: 
    JAP_SS_HISTORICAL = {
	name =  NAME_THEME_HISTORICAL_SUBMARINES  ... } 
    NAME_THEME_HISTORICAL_SUBMARINES used on localisation files
    </p>

