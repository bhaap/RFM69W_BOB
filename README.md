# Breakout PCB for RFM69W radio transceiver 

<img src="https://raw2.github.com/uChip/RFM69W_BOB/master/RFM69W_BOB.png" alt="RFM69W Breakout Board" height="270" width="200"><img src="https://raw2.github.com/uChip/RFM69W_BOB/master/IMG_5882.jpg" alt="RFM69W Breakout Board in action" height="300" width="200">

Eagle CAD PCB designs for radio transceiver breakout board. 
Converts the RFM69W radio transceiver from SMT to 0.1" breadboard format.  This board uses the same pinout as the [JeeLabs RFM12B breakout board] (http://www.digitalsmarties.net/products/rfm12b-board) for compatibility.  Note that this board is NOT compatible with the RFM12B or the RFM69CW.

See the following link for Arduino drivers for the RFM69W  
  * https://github.com/LowPowerLab/RFM69

Hookup of the breakout board to 5V Arduino SPI connection.  All board components populated.  Solder-jumpers left open.  

	Arduino			RFM69W BOB  
	  5V	-->		  5V  
	  GND	<-->	  GND  
	  D11	-->		  SDI  
	  D12	<--		  SDO  
	  D13	-->		  SCK  
	  D10	-->		  SEL  
	  D2	<--		  IRQ  
	  		<--		  3V3  
 
Hookup of the breakout board to 3.3V Arduino SPI connection.  On PCB populate only radio, C2 and C4.  Short the pads on the solder-jumpers.  

	Arduino			RFM69W BOB  
	  NC	 		  5V  
	  GND	<-->	  GND  
	  D11	-->		  SDI  
	  D12	<--		  SDO  
	  D13	-->		  SCK  
	  D10	-->		  SEL  
	  D2	<--		  IRQ  
 	  3.3V	-->		  3V3  


## Order PCBs  

You can order this PCB directly from OSH Park.  Click on the following link.  
  * Radio Breakout - http://oshpark.com/shared_projects/bJRprI06  

See Bill of Materials file in repo for parts list.  

## Status  
  * PCB layout has been tested to be functional.   

## File Formats  

Design files are in "CadSoft EAGLE PCB Design Software" .brd and .sch formats.  
A free version of the software can be downloaded from www.cadsoftusa.com.  

## Distribution License  

You may use this PCB design however you like but no liability is accepted.  