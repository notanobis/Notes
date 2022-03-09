#Programming
Network common data form (NC)

Αυτοπεριγραφόμενο ανεξάρτητο της μηχανής επιστημονικό φορματ δεδομένων

	ncread 
(υψηλού επιπέδου αργη αλλα βολική)

	netcfd.open
(χαμηλού επιπέδου πιο γρήγορη)

ανοιγμα - διάβασμα αρχείου:

	ncid = netcdf.open(file,'NC_NOWRITE');
κλείσιμο :

	netcdf.close(file);

εμφάνιση αρχείου:

	ncdisp(file)

![[Pasted image 20220214003004.png]]