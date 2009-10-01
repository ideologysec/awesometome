SOURCES = 
	SOURCES = advcombat.tex \
	alt.traits.tex \
	armor.tex \
	backgrounds.tex \
	baseclass.tex \
	cover.tex \
	entire.tex \
	feats.tex \
	FiendClasses.tex \
	fiendfeats.tex \
	fiendishrules.tex \
	fiendishtaint.tex \
	fiendspheres.tex \
	magic.tex \
	masscombat.tex \
	multiclassing.tex \
	necrointro.tex \
	necromancerfeats.tex \
	necromaticspells.tex \
	otherspheres.tex \
	prcintro.tex \
	undeadmonsters.tex \
	undead.tex \
	underdark.tex \
	weapons.tex \
	worldwar.tex \
	wrapper.tex \
	baseclasses/adept.tex \
	baseclasses/assassin.tex \
	baseclasses/barbarian.tex \
	baseclasses/conduit.tex \
	baseclasses/elementalist.tex \
	baseclasses/fiendishbrute.tex \
	baseclasses/fighter.tex \
	baseclasses/firemage.tex \
	baseclasses/genie.tex \
	baseclasses/jester.tex \
	baseclasses/knight.tex \
	baseclasses/marshal.tex \
	baseclasses/monk.tex \
	baseclasses/samurai.tex \
	baseclasses/summoner.tex \
	baseclasses/thiefacrobat.tex \
	baseclasses/truefiend.tex \
	baseclasses/warrior.tex \
	skillfeats.tex \
	community/feats/pending/combatfeats.tex \
	community/skillproblems.tex \
	baseclasses/curator.tex \
	baseclasses/kantianpaladin.tex \
	baseclasses/shadowwarrior.tex \
	baseclasses/sohei.tex \
	baseclasses/spherelock.tex \
	prestige/arcanearcher.tex \
	prestige/arcanestrategist.tex \
	prestige/pending/berzerker.tex \
	prestige/bignob.tex \
	prestige/pending/bladefighter.tex \
	prestige/bladesinger.tex \
	prestige/crusaderelemental.tex \
	prestige/defenderofwoods.tex \
	prestige/disciplespiritwave.tex \
	prestige/dragondisciple.tex \
	prestige/drunkenmaster.tex \
	prestige/eldritchknight.tex \
	prestige/enlighteneddisciple.tex \
	prestige/gentlemonk.tex \
	prestige/golemknight.tex \
	prestige/holycrusader.tex \
	prestige/pending/invisibleblade.tex \
	prestige/lunarknight.tex \
	prestige/maelstrom.tex \
	prestige/meteorninja.tex \
	prestige/ogremage.tex \
	prestige/tigermonk.tex \
	monsters/simulacrum.tex \
	prestige/barrister.tex \
	prestige/boatman.tex \
	prestige/bonebladereaper_revised.tex \
	prestige/bonebladereaper.tex \
	prestige/bonerider.tex \
	prestige/celestialbeacon.tex \
	prestige/corpselight.tex \
	prestige/deathking.tex \
	prestige/deathknight.tex \
	prestige/defiler.tex \
	prestige/demonsamurai.tex \
	prestige/dragonlancer.tex \
	prestige/dungeonveteran.tex \
	prestige/ghoulparagon.tex \
	prestige/heartlessmage.tex \
	prestige/hellwalker.tex \
	prestige/initiateofblacktower.tex \
	prestige/legendarystrategist.tex \
	prestige/lorddamned.tex \
	prestige/lurker.tex \
	prestige/masterofnecromanticmysteries.tex \
	prestige/masterofsnakemountain.tex \
	prestige/monitor.tex \
	prestige/ninjaofgax.tex \
	prestige/progenitor.tex \
	prestige/pumpkinking.tex \
	prestige/seekerofthelosttraditions.tex \
	prestige/seeroftempest.tex \
	prestige/skindancer.tex \
	prestige/soulmerchant.tex \
	prestige/speakerfordead.tex \
	prestige/strangerwithburningeyes.tex \
	prestige/swordwraithparagon.tex \
	prestige/thiefofsouls.tex \
	prestige/uttercold.tex \
	prestige/vampireparagon.tex \
	prestige/widowqueen.tex

	
all: entire.pdf

entire.pdf: $(SOURCES)
	# Needs 3 passes to get everything correct.
	pdflatex entire.tex
	pdflatex entire.tex
	pdflatex entire.tex

clean:
	rm -f entire.aux entire.log entire.out entire.pdf entire.toc

.PHONY: clean

complete:
	make clean && make && cp entire.pdf ./TomeTesting.pdf && make clean
