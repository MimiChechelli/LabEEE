# README FOR PROBRAL
# How to Use
1. Download both the code 'LabEEE.ipynb' and the '01. Outdoor-Indoor' folder.
2. Copy and paste its location into the variable 'padrao_busca_csv' with the suffix '/01. LabEEE Experiments/**/*.csv'.
3. You can add IDs to the list named 'ids' to select only the archives that you need.
4. The list 'nao' includes files that you don't need but will be included if not ignored.
5. You can add any codes to the dictionary 'relacao_tabela_informacao' that link individual thermometers spread across participants’ bodies.
6. Add their names to the list 'nomes' and their acronym and acronym + localization number to the dictionary 'ids_com_codigo'.
7. If any sport listed in the chest heart rate monitors table wasn't listed, add its name to the 'sports' list.
8. It takes around 15 minutes to finish and will give you four dataframes. 'BaseDeDados' is the physiological one, 'BaseDeDados ambientais' is the environmental one, 'Dados_qualitativos' is the qualitative data, and 'BaseDeDados_final' is the combined dataset.
