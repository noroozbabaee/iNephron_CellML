SGLT1 Cotransporter
Na-glucose simple cotransporter with 1:1 stoichiometry, located on  Apical  Membrane
return is the transported flux for each solute due to the existance of Na-glucose simple cotransporter.
function to calculate the electrochemical potential of species:(RT)*ln(c) + z*f*V

checking the unit consistency for Electrodiffusive_flux Equation:
[mV] = 1.e-3[V]----> [mV] = 1.e-3 [Joule/Coul]
[xm]---->[Joule/mmol] = [Joule/mmol][1] + [1][Coul/mol][mV]
[xm]---->[Joule/mmol] = [Joule/mmol][1] + [1][Coul/mol]*1.e-3 [ Joule / Coul ]
[xm]---->[Joule/mmol] = [Joule/mmol][1] + [1][Coul/mmol]* 1.e-6 [ Joule / Coul ]
[Electrodiffusive_flux] ----> [mmol/s] = [mmol2/Joule.s]*[Joule/mmol]
    
    