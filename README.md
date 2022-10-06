# Proje 3
## [7, 5, 1, 8, 3, 6, 0, 9, 4, 2] dizisinin Binary-Search-Tree aşamalarını yazınız.


Root = 7

5 < 7 olduğu için sol tarafa yerleşir;
							7					
						*						
					5							
__________________________________________          
1 < 7 olduğu için sol tarafa yerleşir, 1 < 5 olduğu için 5'in soluna yerleşir;

							7					
						*						
					5							
				*								
			1									
__________________________________________
8 > 7 olduğu için sağ tarafa yerleşir ;

							7					
						*		*				
					5				8			
				*								
			1									
_________________________________________

3 < 7 olduğu için sol tarafa yerleşir, 1 < 3 olduğu için 1'in sağına yerleşir;

							7					
						*		*				
					5				8			
				*								
			1									
				*								
					3							
_______________________________________________________________________________
6 < 7  olduğuğu için sol tarafa yerleşir, 5 < 6 olduğu için 5'in sağına yerleşir;

							7					
						*		*				
					5				8			
				*		*						
			1				6					
				*								
					3							
_________________________________________________________________________________
0 < 7 olduğu için sol tarafa yerleşir, 0 < 1 olduğu için 1'in soluna yerleşir;

							7					
						*		*				
					5				8			
				*		*						
			1				6					
		*		*								
	0				3							
____________________________________________________________________________________
7 < 9 olduğu için sağ tarafta yer alır, 8 < 9 olduğu için 8'in sağ tarafına yerleşir;

							7					
						*		*				
					5				8			
				*		*				*		
			1				6				9	
		*		*								
	0				3							
____________________________________________________________________________________
4 < 7 olduğu için sol tarafa yerleşir, 3 < 4 olduğu 3'ün sağına yerleşir;

							7					
						*		*				
					5				8			
				*		*				*		
			1				6				9	
		*		*								
	0				3							
						*						
							4					
____________________________________________________________________________________
2 < 7 olduğu için sol tarafa yerleşir, 2 < 3 olduğu için 3'ün soluna yerleşir;

							7					
						*		*				
					5				8			
				*		*				*		
			1				6				9	
		*		*								
	0				3							
				*		*						
			2				4					

