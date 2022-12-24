# LibreLingo-twi-from-english
LibreLingo Twi course for English speakers

## Initially proposed course structure

- Twi-from-english
	- basics 
		- abd #grammar 
		- pronouns: me, wo, ono, eno, yen, mo, wonom	#grammar
		- diagraphs	#grammar
		- animals 
		- food
		- basic nouns: efie, edan
	- introduction 
		- mepa wo kyewm, akwaaba, medaase, ete sen, aane, daabi
		- me din de, me te, madi mfe, me firi 
	- activities and location
		- ye ne wo, ne ne na 	#grammar
		- verbs: negation 	#grammar
		- movement: ko, ba, firi, nante, dane 
		- dwene, twere, kenkan, kan, kyere, hwoma, kasa, ka, te, te ase, to dwom
	- numbers: 
		- 0-5
		- 5-10
		- 11-20
		- 10-100
		- 0-1000
	- body parts 
		- ti wabeti kotodwe nansoa  
		- rest of body parts 
	- grammar 2
		- prepopisitons: mu, ase, soro, 	#grammar
		- conjunction: ne, na, nanso, se, a, efise, nti	#grammar
		- adjectives: foforo, fefeefe, kesie, dendeende	#grammar
	- home
		- rooms 
		- gegenstaende
	- cooking 
		- food: nua, nam, di, didi, aduane, nso, kube nso, duaba nsu mu, akokonam, aburo
	- questions 
		- questions words
		- grammar sentence order 
	- pronouns and articles
		- obi, obiara, obiara n 
		- articles: no, bi, wei, yi  	#grammar
	- time #grammar
		- time adverbs: seisei, sesiaa, dabiara, okyena, enora, nawotwe, 
		- tenses
		- abo sen, mmere ben, da ben, da bi, 
		- reading the clock
		- week days: dwoada, benada, wukuada, yawoada, fiada, memeneda, kwasiada
		- names
	- going to the market 
	- religion: nyame, onyankopon, awuradee, 
	- nsem den: kwasia, gyimini 

## Useful links

https://github.com/RGBradley/LibreLingo-EU-from-EN
https://github.com/LibreLingo/LibreLingo/discussions/2187
https://github.com/LibreLingo/LibreLingo/blob/main/docs/courses/editing-courses.md
https://github.com/pur80a/LibreLingo

## todo

- make course tree 
- make readme.de 
  - about twi, me amd this course
    - https://www.ghana.gov.gh/mdas/bfc72f13cc/
    - https://www.bg-l.site
  - further learning resources:
    - https://learnakan.com 
    - https://www.kasahorow.org/node/210
    - [google translate](https://translate.google.com/?sl=ak&tl=en)
    - Anki flashcard decks: [conversation](https://ankiweb.net/shared/info/1863265353), [phrases around the house](https://ankiweb.net/shared/info/1898840477), [market](https://ankiweb.net/shared/info/1587304533) and [greetings (not hosted on ankiweb.net anymore)](https://wlankabel.at/john/cloud/twi/Twi_-_Greeting__Responses.apkg) 
- how to help with this course
- process 

## set up of developement environment on macos with homebrew
goes to https://github.com/LibreLingo/LibreLingo/blob/main/docs/index.md 

```
brew update 
brew upgrade 
brew install nvm node poetry yarn 
mkdir ~/.nvm
# into ~/.zshrc
export NVM_DIR="$HOME/.nvm"
[ -s "/opt/homebrew/opt/nvm/nvm.sh" ] && \. "/opt/homebrew/opt/nvm/nvm.sh"  # This loads nvm
[ -s "/opt/homebrew/opt/nvm/etc/bash_completion.d/nvm" ] && \. "/opt/homebrew/opt/nvm/etc/bash_completion.d/nvm"  # This loads nvm bash_completion
#
nvm install 14
reopen shell
git clone git clone git@github.com:LibreLingo/LibreLingo.git LibreLingo.git
cd LibreLingo.git
yarn install 
yarn web dev 
#mkdir -p $HOME/.local/bin 
#export PATH=$PATH:$HOME/.local/bin
#ln -s /opt/homebrew/bin/python3 $HOME/.local/bin/python
yarn web run installAllExternalCourses
#PYTHONPATH=$PYTHONPATH:$PWD/apps/librelingo_types yarn exportAllCourses
python -m venv ../llvenv
source ../llvenv/bin/activate
#######################
pip install regex uni-slugify editdistance click bleach html2markdown markdown yaml8
PYTHONPATH=$PYTHONPATH:$PWD/apps/librelingo_types:$PWD/apps/librelingo_utils:$PWD/apps/librelingo_yaml_loader yarn exportAllCourses
#######################
poetry install
cd apps/librelingo_yaml_loader
poetry install
cd ../../apps/librelingo_json_export
poetry install
cd ../..
#optional
pip install yaml8
yarn exportAllCourses
```

feedback
- mehr saetze 
- frueh coole saetze : affirmations, citate 
- lustige sachen, memes 
- fuer alltag nuetzliche sachen 
- pronomes & affirmations 
- essen und rezepte 
- koerper umd movements 
- deine augen sind gross
- affirmation = pronomen + adjektive 
- affirmation, dann fuehlt man sich gut 
- zahlen + obst
- farben
- trocken und saftige skills abwechselnd 
- wenn kein bild passt nur ein bild aussuchen, damit anker
