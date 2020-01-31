## Cleaning Up CSV Dataset 

* Downloaded original CSV data set to my computer. 
* Uploaded the document to Google Excel
* Sorted row ‘c’ by category name: A-Z
* With Row E Selected: + Match Case for colors
  * If GOLD then Gold
  * If ORANGE then Orange
  * If CREAM then Cream
  * If SILVER then Silver
  * If FUSHIA then Fushia
  * If ROYAL BLUE then Royal Blue
  * If AB BLUE then AB Blue
  * If RED then Red
  * If LIGHT CORAL then Light Coral
  * If PEACH then Peach
  * If BLACK then Black
  * If BLACK DIAMOND then Black Diamond
  * If CLEAR then Clear
  * If MULTI then Multi
  * If MONTANA then Montana
  * If MINT then Mint
  * ETC…
* From Row [ C ]
  * If NECKLACE S then Necklace Sets
*Added missing headers to rows [ H-J ]
* Focusing on filling the blanks in the data in row [ K ]
  * Clicked to row [ N ]
  * Entered Formula =IF(ISBLANK(K2)," No Response", K2)
  * Dragged to copy it dow to the bottom of the dataset
  * Highlighted [ K ] Column
  * selected ‘Paste special **values**’
* Attempted to data validate Row [C] to create drop down categories.
