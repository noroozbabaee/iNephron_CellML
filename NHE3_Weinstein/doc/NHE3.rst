NHE3  Exchanger
----------

NHE3 is an antiporter, located on Apical  Membrane.
There are two different approaches to translate the behavior of Sodium/Hydrogen antiporter in the Weinstein work. 
In the first approach, Weinstein used the equivalent definition of two antiporters: Sodium/Hydrogen and Sodium/Ammonium,
Weinstein 1992, in the way that fluxes are defined based on species' electrochemical potential [Joule/ml]. 
On the second approach [Weinstein_2007], the authors used a detailed kinetical model of the Na+/H+ antiporter from Weinstein 1995. However, the constant parameters in the NHE3 model in 1995 are significantly different from Weinstein_2007.
In the present work, we employ the second approach with the aim of consistency with Weinstein 2007 {Weinstein_2007}.


Parameters definition:

k_nah_Solute: is equilibrium constants of binding that represent the proportion of complexed carrier to
free carrier for each solute and can be represent either according concentration or density;
there will be the same equilibrium constants for external and internal face of the membrane.

k_nah_Solute:{k_nah_na, k_nah_h, k_nah_nh4}

p_nah_Solute: permeation velocity is the coefficient rate of the translocation (of the loaded carrier). 
Permeation velocity increases proportionally with cytosolic acidification. To include this factor, 
Weinstein defined another function called internal modifier; where permeation velocity is a weighted 
average of the maximaland minimum velocity values. 

p_nah_Solute:{p_nah_na, p_nah_h, p_nah_nh4}



In modifirer equations:
f_m and f_M are the minimum and maximum values for sodium permeation respectively.