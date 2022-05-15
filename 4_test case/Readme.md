# High Level Test Cases
# TEST ID	      DESCRIPTION	                          EXPECTED I/P	     EXPECTED O/P	                             ACTUAL O/P     	STATUS
HL01	        check if the BUTTON is pressed	        program execution	      Microcontroller/Engine starts	     LED ON(RED)	        PASS

HL02	        check if the BUTTON is pressed	        program execution      	WIPER starts	                     LED ON(BLUE)	        PASS

HL03	        check if the BUTTON is pressed	        program execution	      WIPER starts	                     LED ON(GREEN)	      partially PASS

HL04	        check if the BUTTON is pressed	        program execution	      WIPER starts	                     LED ON(ORANGE)	      partially PASS


## Low Level Test Cases
# TEST ID	           DESCRIPTION	                 EXPECTED I/P	                      EXPECTED O/P	                    ACTUAL O/P	           STATUS
LL01	         check if the BUTTON is pressed    	program execution     	Microcontroller/Engine starts	                LED ON(RED)            PASS

LL02	         check if the BUTTON is pressed   	program execution	      WIPER starts and speed of wiper is slow     	LED ON(BLUE)           PASS

LL03	         check if the BUTTON is pressed   	program execution	      WIPER starts and speed of wiper is moderate  	LED ON(GREEN)	        partially PASS

LL04	         check if the BUTTON is pressed	    program execution	      WIPER starts and speed of wiper is good	      LED ON(ORANGE)	      partially PASS
