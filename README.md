# LibreLingo-twi-from-english
LibreLingo Twi course for English speakers

Initially proposed course structure
-----------------------------------
- Twi-from-english [*course*] 
	- basics [*module*]
		- animals1 (teach open o and open e) [*skill*]
		- animals2 (teach diagraphs hy, hw, ky, tw, etc
		- pronouns: me, wo, ono, ɛho, yen, mo, wono	
		- basic nouns: efie, edan
	- introduction 
		- greetings
		- mepa wo kyew, akwaaba, medaase, ete sen, aane, daabi
		- basic questions
		- me din de, me te, madi mfe, me firi 
	- family
	- directions (left right, turn, there, here, activity and locations)
	- market (fruits, veggies, meat, seasonings)
	- time week days + adverbs today, now later (when)
	- cooking
	- home (items and rooms)
	- hobbies
	- watch + numbers
	- body parts and movements (head sholders knees and toes)
	- personal hygiene 
	- colors
	- names
	- religion: nyame, onyankopon, awuradee, 
	- nsem den: kwasia, gyimini 
	- proverbs

Each module should have: 
------------------------
- a theme 
- a grammar focus 
- some new words (easily visually representable) 
- new verbs 
- sentences and dialogue excerpts 
	
Grammar to be included into modules and skills: 
-----------------------------------------------
- yɛ vs wɔ
- ne vs na
- negation 
- tenses fut, pres. cont., past, perfect 
- plural 
- negations 
- prepositions 
- questions (sentence order)
- conjunctions
- possesive pronouns 
- articles (no, bi, wei, yi)
- personal pronouns (obi, obiara, obiara en)
- numbers
- cardinal numbers

Words to include:
-----------------
**verbs**: ko, ba, firi, nante, dane, dwene, twere, kenkan, kan, kyere, hwoma, kasa, ka, te, te ase, to dwom, di, didi, nua, nom  
**adjectives**: foforo, fefeefe, kesie, dendeende	
**adverbs**: nso, seisei, sesiara, dabiara, okyena, enora, nawotwe  

## Useful LiLi links

https://github.com/RGBradley/LibreLingo-EU-from-EN  
https://github.com/LibreLingo/LibreLingo/discussions/2187  
https://github.com/LibreLingo/LibreLingo/blob/main/docs/courses/editing-courses.md  
https://github.com/pur80a/LibreLingo  

Usful links: 
------------
  - about twi, me amd this course
    - https://www.ghana.gov.gh/mdas/bfc72f13cc/
    - https://www.bg-l.site
  - further learning resources:
    - https://learnakan.com 
    - https://www.kasahorow.org/node/210
    - [google translate](https://translate.google.com/?sl=ak&tl=en)
    - Anki flashcard decks: [conversation](https://ankiweb.net/shared/info/1863265353), [phrases around the house](https://ankiweb.net/shared/info/1898840477), [market](https://ankiweb.net/shared/info/1587304533) and [greetings (not hosted on ankiweb.net anymore)](https://wlankabel.at/john/cloud/twi/Twi_-_Greeting__Responses.apkg) 
    - [twi courses with syllabus](https://www.amesall.rutgers.edu/academics/undergraduate-program/course-descriptions) 
    - [bible in asante twi](https://www.bible.com/bible/2094/GEN.1.ASNA) (Baoulé and fanti are also available)
    - [Qur'an in twi and arab](https://www.alislam.org/quran/Holy-Quran-Asante.pdf) 
    - [twi dictionary in tabular form](https://web.archive.org/web/20120318225329/http://abibitumikasa.com:80/all.html)
    - [iOS keyboard for Twi, Fante, Ewe and Ga](http://nkyea.com/keyboard.html)
    - [macOS keyboard layout](https://blog.wlankabel.at/2022/05/24/custom-keyboard-layout-macos/) 

ToDos: 
------
- how to help with this course
- process 
- pair themes with grammar focus points
- add this course to the official lili dev courses
- add macos docs to official lili docs 

Set up of developement environment on macos with homebrew
---------------------------------------------------------
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
yarn web dev 
```

feedback
- more sentences
- early cool sentences : affirmations, quotations, proverbs 
- funny things, memes
- useful things for day to day usage
- pronomes & affirmations 
- food and recipes
- body umd movements 
- your eyes are big
- affirmation = pronouns + adjectives 
- affirmations, then one feels better
- numbers + fruits
- colors
- dry and juicy skills alernately
- if no picture fits, choose a single pic as memory anchor

