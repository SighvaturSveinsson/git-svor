#Git spurningar og svör
1. Hvað gera eftirfarandi Linux skipanir?
	cd
		Færir okkur í aðra möppu
	cd ~
		Færir okkur á rótina
	ls
		sýnir skrár í möppuni
	pwd
		sýnir okkur í hvaða möppu við erum í
	mkdir
		gerir nýja möppu

2. Hvað gera eftirfarandi git skipanir og hvers vegna eru þær gagnlegar?
	git clone
		klónar Repository (virkar eins og copy)
	git log
		sýnir hvaða skrám var breytt
	git status
		Sýnir leiðir sem hafa mismuni milli index skrá og núverandi HEAD commit, slóðir sem hafa mismuni milli working tree og index skrá, og leiðir í working tree sem eru ekki raktar
	git diff
		Sýna breytingar milli skráa
	git checkout
		er notað til að velja aðra útgáfu

3. Hver er munurinn á eftirfarandi git skipunum:
	a) git diff 
		Sýna breytingar milli skráa
	b) git diff --staged 
		This form is to view the changes you staged for the next commit relative to the named
		Þetta er notað til að skoða breytingar sem þú staged fyrir næsta commit relative
	c) git diff commit1 commit2
		Displays changes in a repository or a selected set of commits

4. 	Hvað er útgáfustýring (e.version control)?
	Útgáfustýring er kerfi sem skráir breytingar á skrám eða hóp af skrám yfir tíma þannig að þú getur náð í aðrar útgáfur seinna

5.	Hverjir eru helstu kostir við að nota GIT?

6.	Hversu oft telur þú að eigi að gera commit í verkefni, rökstuddu?

7.	Hvað er "Working directory"?" "Staging area"?" og "Repository" í GIT?
		The Git directory is where Git stores the metadata and object database for your project
		Staging area er millisvæði þar sem commits geta verið sniðin og endurskoðuð áður klára drýgja

8.	Hvenær er sniðugt að nota greinar (branches)? 
	Þegar þú ert að vinna í verkefni sem er nú þegar með nokkur commits.

9.	Hver fann upp GIT?
	Linus Torvalds, höfundur Linux

10.	Hvar er GIT helst notað?