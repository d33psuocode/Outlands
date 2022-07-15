Copy each script in this directory to the following in game:
\Kegs\Start
\Kegs\Next
\Kegs\Fill

Setup:
======
1. Organize your workspace near your shelf
2. Add empty kegs to a container
3. Verify your shelf has empty bottles
4. Organize potion bags in containers
   4.a. For each container holding a potion bag
        add to list below so its opened at start
   4.b. Color code your bags
   4.c. Spread them out into several secures nearby
   4.d. Modify list 'boxes' below to add anything holding a bag
        Use command >info to find out box serials
5. Modify the -Start- script to add your serials
6. Choose an alt - shelf profile will be wiped out
7. You MUST stand in a spot where you can reach your boxes,
   and the shelf!

Create following variables:
===========================
kegbox - variable for box/container which holds empty kegs
shelf - your shelf
lpbag - lethal poison bag
dpbag - deadly poison bag
gpbag - greater poison bag
refreshbag - refresh bag
explobag - explo bag
strbag - str bag
dexbag - dex bag
resistbag - resist bag
curebag - cure bag
healbag - heal bag

(Its probably best to save this as a profile so any character can run it)

Create following restock agent:
===============================
restock 3 - keg

This is how I organize my workspace:
====================================

	SECURE BOX 1:
		lpbag
		dpbag
		gpbag

	SECURE BOX 2:
		refreshbag
		explobag
		strbag
		dexbag
		resistbag
		curebag
		healbag
