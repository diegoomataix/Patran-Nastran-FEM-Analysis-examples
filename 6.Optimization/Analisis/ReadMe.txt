%%%%% ReadMe %%%%%

Info de los archivos de solución:

OG --> No tiene solución. Contiene archivo .bdf descargado directamente de Patran.

SOL1 --> CASI CUMPLE FREQ (1.474550E+02). NO CUMPLE STRESS (MOS = 1.73). MASS = 5.212601E+01 kg => 1.801 kg

SOL2 --> CUMPLE FREQ (1.519842E+02 Hz). NO CUMPLE STRESS (MOS = 2.23). MASS = 5.170227E+01 kg => 1.378 kg 

SOL3 --> FALLA EN FREQ (64.7 Hz) PERO CUMPLE REQ. STRESS (MOS = 0.47). MASS = 5.306269E+01 kg => 2.738 kg

SOL4 --> CUMPLE FREQ (150.94 Hz) NO CUMPLE REQ. STRESS (MOS = 2.13). MASS = 5.166991E+01 kg => 1.345 kg
     --> edit --> igualando altura rigidizadores: (Sat_Bandeja_Inf_9rig_I_Al7075_SOL4)
		--- MASS = 5.166991E+01 kg => 1.345 kg
		--- 1 FREQ = 1.508950E+02 Hz
		--- MOS = 2.13
	
SOL5 --> CUMPLE FREQ (150.39 Hz) PERO CUMPLE REQ. STRESS (MOS = 2.31). MASS =  5.179465E+01 kg => 1.470 kg
 

----------------------------------------------------------------------------------------------------------

Rin --> Element 4000:4299

Rout --> Element 4500:4559

Shell --> Element 1000:1359 3000:3179