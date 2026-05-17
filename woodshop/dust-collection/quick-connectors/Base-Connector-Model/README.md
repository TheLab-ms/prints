
Source Files for the large machine quick connectors used in TheLab

Files:
TheLab_Large_Machine_Connector_Source.f3d: Fusion 360 Model modified for a better connection to a 4" hose
	This very much resembles to original model
	We do not have a Fusion 360 model of TheLabs version of the Hose side, due to
	lack of F360 know how. It was stitched together using Bambu Studio

TheLab_Large_Machine_Connector_Machine_Side_No_Ribs.f3d
	A sample of a machine side connector. This has removed the internal ribs so the
	connector mates smoothly with the machines external port.
	The tube portion in this model has been resized to fit snuggly on the table saw.
	Each machine will need to be adjusted for a best fit.


Bambu-Exports:

   Bambu_Modified_Machine_Side.stl:
	Because our machines contain dust collector flanges that we would rather
	not remove, this idea was to remove the internal ribs and adjust the inside
	diameter so it will fit snuggly "over" the existing machine flanges.
	Turns out for a good fit each machine has this part customized. This is the
	machine side with the ribs intact. 
	
   Bambu_Modified_Hose_Side.stl:
	This was the "original" designs machine side, but due to minimal knowledge of
	Fusion 360, we within Bambu cut the tube portion from the original "hose side"
	and added it to the "original machine" side. This becomes "our hose side. 
	(Yes we messed up that one should have just modified the "original machine" 
	side, would have been less convoluted)

   Bambu_Modified_Hose_Side_Split_For_No_Support_Print.stl:
	If the new hose side is printed as designed it would require a large amount
	of supports and print time, So it was split into two pieces that could
	printed without supports, then glued together when printed.
