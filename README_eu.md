<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# motionEye YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/motioneye.svg)](https://dash.yunohost.org/appci/app/motioneye) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/motioneye.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/motioneye.maintain.svg)

[![Instalatu motionEye YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=motioneye)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek motionEye YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

**motionEye** is an online interface for the software [_motion_](https://motion-project.github.io/), a video surveillance program with motion detection.

Check out the [__wiki__](https://github.com/motioneye-project/motioneye/wiki) for more details.

Default user for login is: `admin` and empty password.


**Paketatutako bertsioa:** 0.43.1b1~ynh1

## Pantaila-argazkiak

![motionEye(r)en pantaila-argazkia](./doc/screenshots/example.png)

## Dokumentazioa eta baliabideak

- Erabiltzaileen dokumentazio ofiziala: <https://github.com/motioneye-project/motioneye/wiki>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/motioneye-project/motioneye>
- YunoHost Denda: <https://apps.yunohost.org/app/motioneye>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/motioneye_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/motioneye_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/motioneye_ynh/tree/testing --debug
edo
sudo yunohost app upgrade motioneye -u https://github.com/YunoHost-Apps/motioneye_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
