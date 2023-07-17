# The Pyrfume Public Data Archive
## Wrangled, pre-processed, and curated olfactory psychophysics and biology data.

![pyrfume-logo](https://avatars.githubusercontent.com/u/34174393)

Intended for use with the `pyrfume` Python library:
```console
pip install pyrfume
```

Examples:
```python
import pyrfume
```
followed by e.g.:

```python
# Load all the data from Bushdid et al, 2014 ("Humans Can Discriminate More than 1 Trillion Olfactory Stimuli")
molecules = pyrfume.load_data('bushdid_2014/molecules.csv')
mixtures = pyrfume.load_data('bushdid_2014/mixtures.csv')
behavior = pyrfume.load_data('bushdid_2014/behavior.csv')
```
or e.g.:

```python
# Load all the data from Snitz et al, 2013 ("Predicting Odor Perceptual Similarity from Odor Structure")
molecules = pyrfume.load_data('snitz_2013/molecules.csv')
behavior = pyrfume.load_data('snitz_2013/behavior.csv')
```

Analogous examples can be found [here](code_examples.py) for other datasets.

## Current inventory:
[![abraham_2012](https://img.shields.io/static/v1?label=&nbsp;&message=abraham_2012&color=eeeeee)](#) [![<human>](https://img.shields.io/static/v1?label=organism&message=human&color=ff753c)](#) [![<threshold>](https://img.shields.io/static/v1?label=data&message=threshold&color=1cd1e2)](#) [![<academic>](https://img.shields.io/static/v1?label=source&message=academic&color=3175f7)](#) <br>[![ahmed_2018](https://img.shields.io/static/v1?label=&nbsp;&message=ahmed_2018&color=eeeeee)](#) [![<receptorResponse>](https://img.shields.io/static/v1?label=data&message=receptorResponse&color=ff3b1d)](#) [![<academic>](https://img.shields.io/static/v1?label=source&message=academic&color=3175f7)](#) <br>[![arctander_1960](https://img.shields.io/static/v1?label=&nbsp;&message=arctander_1960&color=eeeeee)](#) [![<human>](https://img.shields.io/static/v1?label=organism&message=human&color=ff753c)](#) [![<odorCharacter>](https://img.shields.io/static/v1?label=data&message=odorCharacter&color=09a9ee)](#) <br>[![aromadb](https://img.shields.io/static/v1?label=&nbsp;&message=aromadb&color=eeeeee)](#) [![<human>](https://img.shields.io/static/v1?label=organism&message=human&color=ff753c)](#) [![<odorCharacter>](https://img.shields.io/static/v1?label=data&message=odorCharacter&color=09a9ee)](#) <br>[![arshamian_2022](https://img.shields.io/static/v1?label=&nbsp;&message=arshamian_2022&color=eeeeee)](#) [![<human>](https://img.shields.io/static/v1?label=organism&message=human&color=ff753c)](#) [![<pleasantness>](https://img.shields.io/static/v1?label=data&message=pleasantness&color=44eed1)](#) [![<academic>](https://img.shields.io/static/v1?label=source&message=academic&color=3175f7)](#) <br>[![bolding_2018](https://img.shields.io/static/v1?label=&nbsp;&message=bolding_2018&color=eeeeee)](#) [![<rodent>](https://img.shields.io/static/v1?label=organism&message=rodent&color=7f00ff)](#) [![<academic>](https://img.shields.io/static/v1?label=source&message=academic&color=3175f7)](#) <br>[![burton_2022](https://img.shields.io/static/v1?label=&nbsp;&message=burton_2022&color=eeeeee)](#) [![<rodent>](https://img.shields.io/static/v1?label=organism&message=rodent&color=7f00ff)](#) [![<receptorResponse>](https://img.shields.io/static/v1?label=data&message=receptorResponse&color=ff3b1d)](#) [![<academic>](https://img.shields.io/static/v1?label=source&message=academic&color=3175f7)](#) <br>[![bushdid_2014](https://img.shields.io/static/v1?label=&nbsp;&message=bushdid_2014&color=eeeeee)](#) [![<human>](https://img.shields.io/static/v1?label=organism&message=human&color=ff753c)](#) [![<odorCharacter>](https://img.shields.io/static/v1?label=data&message=odorCharacter&color=09a9ee)](#) [![<academic>](https://img.shields.io/static/v1?label=source&message=academic&color=3175f7)](#) <br>[![chae_2019](https://img.shields.io/static/v1?label=&nbsp;&message=chae_2019&color=eeeeee)](#) [![<rodent>](https://img.shields.io/static/v1?label=organism&message=rodent&color=7f00ff)](#) [![<receptorResponse>](https://img.shields.io/static/v1?label=data&message=receptorResponse&color=ff3b1d)](#) [![<academic>](https://img.shields.io/static/v1?label=source&message=academic&color=3175f7)](#) <br>[![dravnieks_1985](https://img.shields.io/static/v1?label=&nbsp;&message=dravnieks_1985&color=eeeeee)](#) [![<human>](https://img.shields.io/static/v1?label=organism&message=human&color=ff753c)](#) [![<odorCharacter>](https://img.shields.io/static/v1?label=data&message=odorCharacter&color=09a9ee)](#) [![<academic>](https://img.shields.io/static/v1?label=source&message=academic&color=3175f7)](#) <br>[![flavordb](https://img.shields.io/static/v1?label=&nbsp;&message=flavordb&color=eeeeee)](#) [![<human>](https://img.shields.io/static/v1?label=organism&message=human&color=ff753c)](#) [![<odorCharacter>](https://img.shields.io/static/v1?label=data&message=odorCharacter&color=09a9ee)](#) <br>[![flavornet](https://img.shields.io/static/v1?label=&nbsp;&message=flavornet&color=eeeeee)](#) [![<human>](https://img.shields.io/static/v1?label=organism&message=human&color=ff753c)](#) [![<odorCharacter>](https://img.shields.io/static/v1?label=data&message=odorCharacter&color=09a9ee)](#) <br>[![foodb](https://img.shields.io/static/v1?label=&nbsp;&message=foodb&color=eeeeee)](#) [![<human>](https://img.shields.io/static/v1?label=organism&message=human&color=ff753c)](#) [![<odorCharacter>](https://img.shields.io/static/v1?label=data&message=odorCharacter&color=09a9ee)](#) <br>[![foodcomex](https://img.shields.io/static/v1?label=&nbsp;&message=foodcomex&color=eeeeee)](#) <br>[![fragrancedb](https://img.shields.io/static/v1?label=&nbsp;&message=fragrancedb&color=eeeeee)](#) <br>[![freesolve](https://img.shields.io/static/v1?label=&nbsp;&message=freesolve&color=eeeeee)](#) [![<human>](https://img.shields.io/static/v1?label=organism&message=human&color=ff753c)](#) [![<odorCharacter>](https://img.shields.io/static/v1?label=data&message=odorCharacter&color=09a9ee)](#) <br>[![goodscents](https://img.shields.io/static/v1?label=&nbsp;&message=goodscents&color=eeeeee)](#) [![<human>](https://img.shields.io/static/v1?label=organism&message=human&color=ff753c)](#) [![<odorCharacter>](https://img.shields.io/static/v1?label=data&message=odorCharacter&color=09a9ee)](#) <br>[![gras](https://img.shields.io/static/v1?label=&nbsp;&message=gras&color=eeeeee)](#) <br>[![haddad_2008](https://img.shields.io/static/v1?label=&nbsp;&message=haddad_2008&color=eeeeee)](#) [![<human>](https://img.shields.io/static/v1?label=organism&message=human&color=ff753c)](#) [![<rodent>](https://img.shields.io/static/v1?label=organism&message=rodent&color=7f00ff)](#) [![<academic>](https://img.shields.io/static/v1?label=source&message=academic&color=3175f7)](#) <br>[![ifra_2019](https://img.shields.io/static/v1?label=&nbsp;&message=ifra_2019&color=eeeeee)](#) [![<human>](https://img.shields.io/static/v1?label=organism&message=human&color=ff753c)](#) [![<odorCharacter>](https://img.shields.io/static/v1?label=data&message=odorCharacter&color=09a9ee)](#) <br>[![iurilli_2017](https://img.shields.io/static/v1?label=&nbsp;&message=iurilli_2017&color=eeeeee)](#) [![<rodent>](https://img.shields.io/static/v1?label=organism&message=rodent&color=7f00ff)](#) [![<academic>](https://img.shields.io/static/v1?label=source&message=academic&color=3175f7)](#) <br>[![jones_2019](https://img.shields.io/static/v1?label=&nbsp;&message=jones_2019&color=eeeeee)](#) [![<rodent>](https://img.shields.io/static/v1?label=organism&message=rodent&color=7f00ff)](#) [![<receptorResponse>](https://img.shields.io/static/v1?label=data&message=receptorResponse&color=ff3b1d)](#) [![<academic>](https://img.shields.io/static/v1?label=source&message=academic&color=3175f7)](#) [![<threshold>](https://img.shields.io/static/v1?label=data&message=threshold&color=1cd1e2)](#) <br>[![keller_2012](https://img.shields.io/static/v1?label=&nbsp;&message=keller_2012&color=eeeeee)](#) [![<human>](https://img.shields.io/static/v1?label=organism&message=human&color=ff753c)](#) [![<intensity>](https://img.shields.io/static/v1?label=data&message=intensity&color=baee90)](#) [![<pleasantness>](https://img.shields.io/static/v1?label=data&message=pleasantness&color=44eed1)](#) [![<odorCharacter>](https://img.shields.io/static/v1?label=data&message=odorCharacter&color=09a9ee)](#) [![<threshold>](https://img.shields.io/static/v1?label=data&message=threshold&color=1cd1e2)](#) [![<academic>](https://img.shields.io/static/v1?label=source&message=academic&color=3175f7)](#) <br>[![keller_2016](https://img.shields.io/static/v1?label=&nbsp;&message=keller_2016&color=eeeeee)](#) [![<human>](https://img.shields.io/static/v1?label=organism&message=human&color=ff753c)](#) [![<intensity>](https://img.shields.io/static/v1?label=data&message=intensity&color=baee90)](#) [![<pleasantness>](https://img.shields.io/static/v1?label=data&message=pleasantness&color=44eed1)](#) [![<familiarity>](https://img.shields.io/static/v1?label=data&message=familiarity&color=6cfdbe)](#) [![<odorCharacter>](https://img.shields.io/static/v1?label=data&message=odorCharacter&color=09a9ee)](#) [![<academic>](https://img.shields.io/static/v1?label=source&message=academic&color=3175f7)](#) <br>[![knapsack](https://img.shields.io/static/v1?label=&nbsp;&message=knapsack&color=eeeeee)](#) <br>[![leffingwell](https://img.shields.io/static/v1?label=&nbsp;&message=leffingwell&color=eeeeee)](#) [![<human>](https://img.shields.io/static/v1?label=organism&message=human&color=ff753c)](#) [![<odorCharacter>](https://img.shields.io/static/v1?label=data&message=odorCharacter&color=09a9ee)](#) <br>[![leon](https://img.shields.io/static/v1?label=&nbsp;&message=leon&color=eeeeee)](#) [![<rodent>](https://img.shields.io/static/v1?label=organism&message=rodent&color=7f00ff)](#) [![<imaging>](https://img.shields.io/static/v1?label=data&message=imaging&color=ffa95a)](#) [![<olfactoryBulb>](https://img.shields.io/static/v1?label=data&message=olfactoryBulb&color=ff0000)](#) <br>[![ma_2012](https://img.shields.io/static/v1?label=&nbsp;&message=ma_2012&color=eeeeee)](#) [![<rodent>](https://img.shields.io/static/v1?label=organism&message=rodent&color=7f00ff)](#) [![<receptorResponse>](https://img.shields.io/static/v1?label=data&message=receptorResponse&color=ff3b1d)](#) [![<academic>](https://img.shields.io/static/v1?label=source&message=academic&color=3175f7)](#) <br>[![ma_2021](https://img.shields.io/static/v1?label=&nbsp;&message=ma_2021&color=eeeeee)](#) [![<human>](https://img.shields.io/static/v1?label=organism&message=human&color=ff753c)](#) [![<intensity>](https://img.shields.io/static/v1?label=data&message=intensity&color=baee90)](#) [![<pleasantness>](https://img.shields.io/static/v1?label=data&message=pleasantness&color=44eed1)](#) [![<mixtures>](https://img.shields.io/static/v1?label=stimuli&message=mixtures&color=92fda9)](#) [![<academic>](https://img.shields.io/static/v1?label=source&message=academic&color=3175f7)](#) <br>[![mainland_2015](https://img.shields.io/static/v1?label=&nbsp;&message=mainland_2015&color=eeeeee)](#) [![<human>](https://img.shields.io/static/v1?label=organism&message=human&color=ff753c)](#) [![<receptorResponse>](https://img.shields.io/static/v1?label=data&message=receptorResponse&color=ff3b1d)](#) [![<academic>](https://img.shields.io/static/v1?label=source&message=academic&color=3175f7)](#) <br>[![manoel_2021](https://img.shields.io/static/v1?label=&nbsp;&message=manoel_2021&color=eeeeee)](#) [![<rodent>](https://img.shields.io/static/v1?label=organism&message=rodent&color=7f00ff)](#) [![<odorCharacter>](https://img.shields.io/static/v1?label=data&message=odorCharacter&color=09a9ee)](#) [![<academic>](https://img.shields.io/static/v1?label=source&message=academic&color=3175f7)](#) <br>[![mayhew_2022](https://img.shields.io/static/v1?label=&nbsp;&message=mayhew_2022&color=eeeeee)](#) [![<human>](https://img.shields.io/static/v1?label=organism&message=human&color=ff753c)](#) [![<academic>](https://img.shields.io/static/v1?label=source&message=academic&color=3175f7)](#) <br>[![nagappan_2021](https://img.shields.io/static/v1?label=&nbsp;&message=nagappan_2021&color=eeeeee)](#) [![<rodent>](https://img.shields.io/static/v1?label=organism&message=rodent&color=7f00ff)](#) [![<academic>](https://img.shields.io/static/v1?label=source&message=academic&color=3175f7)](#) [![<electrophysiology>](https://img.shields.io/static/v1?label=data&message=electrophysiology&color=593bfd)](#) <br>[![nakayama_2022](https://img.shields.io/static/v1?label=&nbsp;&message=nakayama_2022&color=eeeeee)](#) [![<rodent>](https://img.shields.io/static/v1?label=organism&message=rodent&color=7f00ff)](#) [![<odorCharacter>](https://img.shields.io/static/v1?label=data&message=odorCharacter&color=09a9ee)](#) [![<academic>](https://img.shields.io/static/v1?label=source&message=academic&color=3175f7)](#) <br>[![nat_geo_1986](https://img.shields.io/static/v1?label=&nbsp;&message=nat_geo_1986&color=eeeeee)](#) [![<human>](https://img.shields.io/static/v1?label=organism&message=human&color=ff753c)](#) [![<odorCharacter>](https://img.shields.io/static/v1?label=data&message=odorCharacter&color=09a9ee)](#) <br>[![nhanes_2014](https://img.shields.io/static/v1?label=&nbsp;&message=nhanes_2014&color=eeeeee)](#) [![<human>](https://img.shields.io/static/v1?label=organism&message=human&color=ff753c)](#) [![<odorCharacter>](https://img.shields.io/static/v1?label=data&message=odorCharacter&color=09a9ee)](#) <br>[![optical_rotation](https://img.shields.io/static/v1?label=&nbsp;&message=optical_rotation&color=eeeeee)](#) <br>[![prestwick](https://img.shields.io/static/v1?label=&nbsp;&message=prestwick&color=eeeeee)](#) <br>[![ravia_2020](https://img.shields.io/static/v1?label=&nbsp;&message=ravia_2020&color=eeeeee)](#) [![<human>](https://img.shields.io/static/v1?label=organism&message=human&color=ff753c)](#) [![<odorCharacter>](https://img.shields.io/static/v1?label=data&message=odorCharacter&color=09a9ee)](#) [![<mixtures>](https://img.shields.io/static/v1?label=stimuli&message=mixtures&color=92fda9)](#) [![<academic>](https://img.shields.io/static/v1?label=source&message=academic&color=3175f7)](#) <br>[![scott_2014](https://img.shields.io/static/v1?label=&nbsp;&message=scott_2014&color=eeeeee)](#) [![<rodent>](https://img.shields.io/static/v1?label=organism&message=rodent&color=7f00ff)](#) [![<academic>](https://img.shields.io/static/v1?label=source&message=academic&color=3175f7)](#) <br>[![sharma_2021a](https://img.shields.io/static/v1?label=&nbsp;&message=sharma_2021a&color=eeeeee)](#) [![<odorCharacter>](https://img.shields.io/static/v1?label=data&message=odorCharacter&color=09a9ee)](#) <br>[![sharma_2021b](https://img.shields.io/static/v1?label=&nbsp;&message=sharma_2021b&color=eeeeee)](#) [![<human>](https://img.shields.io/static/v1?label=organism&message=human&color=ff753c)](#) [![<odorCharacter>](https://img.shields.io/static/v1?label=data&message=odorCharacter&color=09a9ee)](#) <br>[![sigma_2014](https://img.shields.io/static/v1?label=&nbsp;&message=sigma_2014&color=eeeeee)](#) [![<human>](https://img.shields.io/static/v1?label=organism&message=human&color=ff753c)](#) [![<odorCharacter>](https://img.shields.io/static/v1?label=data&message=odorCharacter&color=09a9ee)](#) <br>[![slone_2017](https://img.shields.io/static/v1?label=&nbsp;&message=slone_2017&color=eeeeee)](#) [![<harpegnathos>](https://img.shields.io/static/v1?label=organism&message=harpegnathos&color=e2d175)](#) [![<receptorResponse>](https://img.shields.io/static/v1?label=data&message=receptorResponse&color=ff3b1d)](#) [![<academic>](https://img.shields.io/static/v1?label=source&message=academic&color=3175f7)](#) <br>[![snitz_2013](https://img.shields.io/static/v1?label=&nbsp;&message=snitz_2013&color=eeeeee)](#) [![<human>](https://img.shields.io/static/v1?label=organism&message=human&color=ff753c)](#) [![<odorCharacter>](https://img.shields.io/static/v1?label=data&message=odorCharacter&color=09a9ee)](#) [![<mixtures>](https://img.shields.io/static/v1?label=stimuli&message=mixtures&color=92fda9)](#) [![<academic>](https://img.shields.io/static/v1?label=source&message=academic&color=3175f7)](#) <br>[![snitz_2019](https://img.shields.io/static/v1?label=&nbsp;&message=snitz_2019&color=eeeeee)](#) [![<human>](https://img.shields.io/static/v1?label=organism&message=human&color=ff753c)](#) [![<intensity>](https://img.shields.io/static/v1?label=data&message=intensity&color=baee90)](#) [![<odorCharacter>](https://img.shields.io/static/v1?label=data&message=odorCharacter&color=09a9ee)](#) [![<academic>](https://img.shields.io/static/v1?label=source&message=academic&color=3175f7)](#) <br>[![soh_2013](https://img.shields.io/static/v1?label=&nbsp;&message=soh_2013&color=eeeeee)](#) [![<rodent>](https://img.shields.io/static/v1?label=organism&message=rodent&color=7f00ff)](#) <br>[![superscent](https://img.shields.io/static/v1?label=&nbsp;&message=superscent&color=eeeeee)](#) <br>[![t3db](https://img.shields.io/static/v1?label=&nbsp;&message=t3db&color=eeeeee)](#) <br>[![wakayama_2019](https://img.shields.io/static/v1?label=&nbsp;&message=wakayama_2019&color=eeeeee)](#) [![<human>](https://img.shields.io/static/v1?label=organism&message=human&color=ff753c)](#) [![<intensity>](https://img.shields.io/static/v1?label=data&message=intensity&color=baee90)](#) <br>[![weiss_2012](https://img.shields.io/static/v1?label=&nbsp;&message=weiss_2012&color=eeeeee)](#) [![<human>](https://img.shields.io/static/v1?label=organism&message=human&color=ff753c)](#) [![<odorCharacter>](https://img.shields.io/static/v1?label=data&message=odorCharacter&color=09a9ee)](#) [![<academic>](https://img.shields.io/static/v1?label=source&message=academic&color=3175f7)](#) <br>[![yu_2015](https://img.shields.io/static/v1?label=&nbsp;&message=yu_2015&color=eeeeee)](#) [![<receptorResponse>](https://img.shields.io/static/v1?label=data&message=receptorResponse&color=ff3b1d)](#) [![<academic>](https://img.shields.io/static/v1?label=source&message=academic&color=3175f7)](#) <br>