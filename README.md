# Stagesoft project

**cuems** suite is a new open source software project from [Stagelab](https://www.stagelab.net) and [bTactic](https://www.btactic.com).

![Stagelab logo]([https://www.stagelab.net/wp-content/uploads/2017/02/logo_stagelab_x80_gris.png](https://stagelab.coop/wp-content/uploads/2021/05/stagelabcoop_head.png)) ![bTactic logo](https://www.btactic.com/wp-content/uploads/2018/10/logo-btactic.png)

**cuems** suite will not only manage cues but also network connected external devices.

Its main audience is theatre and live entertainment technicians.

cuems will try to reuse and improve other open source projects such as:

* [xjadeo](https://github.com/stagesoft/xjadeo)

cuems will generate new projects from scratch like:

* [cuems-engine](https://github.com/stagesoft/cuems-engine)
* [cuems_editor](https://github.com/stagesoft/cuems_editor)
* [libmtcmaster](https://github.com/stagesoft/libmtcmaster)
* [cuems-audioplayer](https://github.com/stagesoft/cuems-audioplayer)

You can find our newest repositories at: [Stagesoft org page](https://github.com/stagesoft).

And our packages repository at: [Stagesoft package repo](https://repo.stagelab.net)

(debian 10 packages, amd64, dbgsym and source)

Instructions to add the repo to debian 10 buster:

First add the key used to sing the packages & repo:

`wget -q -O - https://repo.stagelab.net/repo.stagelab.key |sudo apt-key add -`

Then add the repo to a new sources.list.d/ file:

`sudo wget -O /etc/apt/sources.list.d/stagelab.list https://repo.stagelab.net/stagelab.list`

Or manually:
`deb https://repo.stagelab.net/debian buster main`
`deb-src https://repo.stagelab.net/debian buster main`

list of packages curretly on the repo: (work in progress, unstable packages at the moment for testing purpouses)
* cuems-audioplayer
* libmtcmaster
* xjadeo
* jackd2
* libossia
* cmake
 
 
.
 
 
 
This project it's funded by:
![funded_by_logos](https://dev.stagelab.net/logos/logos_finan.png)
