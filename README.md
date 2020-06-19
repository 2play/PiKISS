# PiKISS for Raspberry Pi: A bunch of scripts with menu to make your life easier.

![PiKISS Logo](logo_pikiss_400.png)

<p align="center">
	<a href='https://ko-fi.com/A838QJC' target='_blank'><img height='36' style='border:0px;height:36px;' src='https://az743702.vo.msecnd.net/cdn/kofi2.png?v=0' border='0' alt='Buy Me a Coffee at ko-fi.com' /></a>
	<a href="https://github.com/jmcerrejon/neighborhood-games/blob/master/LICENSE"><img src="https://img.shields.io/github/license/jmcerrejon/neighborhood-games" alt="npm version"></a>
	<a href="https://twitter.com/ulysess10"><img src="https://img.shields.io/twitter/follow/ulysess10?style=social" alt="Follow me on Twitter!"></a>
</p>

Estimated hours of work so far | Horas estimadas de trabajo hasta el momento:

* **559 hours**

* Total amount donated by users: $14.11

Contributors:

* [huelvayork](https://github.com/huelvayork)

## ENGLISH

### [ Screenshots ]

![piKiss_01](screenshots/pikiss_twisterOS_01.png)

![piKiss_02](screenshots/pikiss_twisterOS_02.png)

![piKiss_03](screenshots/pikiss_twisterOS_03.png)

![piKiss_04](screenshots/pikiss_twisterOS_04.png)


### [ ChangeLog (dd/mm/yy)]

### (19/06/20)

· 📦 ADD: mGBA v0.90, Mednafen 1.24.3.

· ❌ REMOVE: DPRCZ/gpsp, PC-Engine.

· 👌 IMPROVE: OpenMSX.

### (18/06/20)

· 📦 ADD: Abbaye des Morts v2.0.0.

· 📦 ADD: DOSBox-X v0.82, Amiberry v3.1.3.1.

· ❌ REMOVE: rpix86, 8086tiny, UAE4ARM.

### (17/06/20)

· 👌 IMPROVE: MAME.

### (16/06/20)

· 👌 IMPROVE: SuperNES emulator (Snes9X 1.60).

### (15/06/20)

· ❌ REMOVE: piKiss.sh > GMaker, RWolf, Giana & Fruity (Not supported anymore).

· 👌 IMPROVE: Caprice32 (Amstrad).

### (12/06/20)

· 🐛 FIX: Doom, Heretic. Removed Hexen, Strife (check Crispy-doom Github issue).

· 📦 IMPROVE: Helper now install Box86, GL4ES, Mesa or Mono libs when is needed. 

### (08/06/20)

· 🐛 FIX: Diablo 1.

### (02/04/20)

· Updated Spectrum emulator unrealspeccy to 0.86.11

### (08/03/20)

· Fix Games > Revolt.

### (07/03/20)

· Update Games > Crispy Doom.

### (16/11/19)

· Add Games > Diablo 2 LOD Spanish Ed.

### (02/10/19)

· Add Games > Diablo 1

...

To see the full list of changes, read the [CHANGELOG](./CHANGELOG)

### [ Introducing PiKISS ]

Install an application on Linux is not a complex task. Sometimes just type *sudo apt install* and get the application installed with all its dependencies. But... What if we need to install more than one app such as a web server or it requires many steps to complete the install process?, Is it not in the official repositories?, What if you want to get rid of input commands?. Please, an easy way to set up my WIFI network!.

Don't despair. **PiKISS** has come to help you...

- - -
**PiKISS** *(Pi Keeping It Simple, Stupid!)* are *scripts (Bash)* for *Raspberry Pi* boards (*Raspbian* mainly, [TwisterOS](https://raspbian-x.com/) and *Debian* derivates), which has a menu that will allow you to install some applications or configure files automatically as easy as possible.

The idea is to offer facilities to manage your operating system, selecting an option in a menu and answer [Yes/No]. If you need to check dependencies, install an app, modify a script at boot, add a line to a file or download other, **PiKISS** will do it for you.

I include not only the ability to install, but also compile programs. Do you have problems when compiling your favorite emulator?, Have you forgotten to modify a line in the source code and now you have to recompile again for 4 hours?. Laugh your now all this with **PiKISS**.

What some users have said about **PiKISS**:

* *"It could have happened to me!"*

* *"That's silly! (I'm going to install it as soon as I get home)"*

* *"I don't need to fight with the terminal anymore? Shut up and take my money!."* - Easy, it's free.

**NOTE:** 100% Free of viruses and Trojans. Not available in stores. The author of **PiKISS** is not responsible if you get bored with your *Raspberry Pi* because everything is too easy. Online until I wish or *Internet* is destroyed.

#### [ Installation ]

Just type:

<pre>
git clone https://github.com/jmcerrejon/PiKISS.git piKiss && cd $_
./piKiss.sh
</pre>

#### [ Update ]

 If you want the latest version, just enter into the directory with cd PiKISS and type:

<pre>
git pull
</pre>

NOTE: If you use another distribution other than *Raspbian/TwisterOS*, maybe you need to execute the next command: *git config --global http.sslVerify false*

#### [ HELP ME! ]

**PiKISS** grow up according to users requests or I'll append scripts that I consider necessary, but I call **to the community** to share, improve and help to add new scripts to the existing one. If the project grow, **is up to you**.

José Cerrejón [(@ulysess10)](https://twitter.com/ulysess10)

Mail: <ulysess@gmail.com>

Blog: [https://misapuntesde.com](https://misapuntesde.com)

#### [ DONATE ]

This project has involved many hours thinking, searching, refactoring and testing code. I accept donations due the effort to make new scripts. Donations are not required or expected. Any amount that you feel is appropriate would be appreciated. Simply click on the Donate button at the end of this document. Thank you! :)

## ESPAÑOL

## PiKISS para Raspberry Pi: Un puñado de scripts con menú para hacerte la vida más fácil.

#### [ Presentando PiKISS ]

Instalar una aplicación en Linux no es complejo. A veces basta con un *sudo apt install* y tendrás la aplicación con todas sus dependencias. Pero, ¿Y si tenemos que instalar más de una app como por ejemplo en un servidor web o necesita varios pasos para completar el proceso de instalación?, ¿Y si no está en los repositorios oficiales?, ¿Y si no quieres teclear? ¡Por favor, una manera fácil de instalar mi red WIFI!.

No desesperéis. Ha llegado **PiKISS** para ayudarte...

- - -
**PiKISS** *(Pi Keeping It Simple, Stupid!, "Pi manteniéndolo sencillo, ¡Estúpido!")* son unos *scripts en Bash* para placas *Raspberry Pi* (*Raspbian*, [TwisterOS](https://raspbian-x.com/) y derivados *Debian*), que cuenta con un menú que te va a permitir instalar algunas aplicaciones o configurar ficheros de forma automática de la manera más fácil posible. **Su misión: Simplificar la instalación de software en *Raspberry Pi* o en *ODROID-C1* y mantenerla.**

La idea es ofrecer facilidades para manejar tu distribución y que las instalaciones sean tan sencillas como seleccionar una opción en un menú y contestar [Si/No]. Si alguna conlleva algo más que instalar, por ejemplo modificar un script en el arranque, añadir una línea a un fichero, descargar otros ficheros, comprobar dependencias, **PiKISS** lo hará por ti.

Incluyo la posibilidad no solo de instalar, sino también de compilar programas. ¿Problemas a la hora de compilar tu emulador favorito?, ¿Se te ha olvidado modificar una línea en el código fuente de su autor y tienes que volver a recompilar durante 4 horas?. Ríete tú ahora de todo esto con **PiKISS**.

Lo que algunos usuarios han dicho de **PiKISS**:

*"¡Se me podría haber ocurrido a mí!"*

*"Menuda tontería (voy a instalarlo en cuanto llegue a casa)"*

*"¿Ya no tengo que pelearme con la terminal?. Cállate y coge mi dinero!"* - Tranquilos, es gratis.

**NOTA:** 100% Libre de virus y troyanos. No disponible en tiendas. El autor de *PiKISS* no se hace responsable si te aburres con tu *Raspberry Pi* porque todo es demasiado fácil. Online hasta que me plazca o se destruya *Internet*.

#### [ Instalación ]

Escribe en la terminal lo siguiente:

<pre>
git clone https://github.com/jmcerrejon/PiKISS.git && cd PiKISS
./piKiss.sh
</pre>

#### [ Actualizar ]

Si ya la tienes instalada y quieres actualizarla con los últimos cambios, teclea en el directorio de *PiKISS*:

<pre>
git pull
</pre>

NOTA: Si usas otra distribución que no sea *Raspbian/TwisterOS* en la *Raspberry Pi*, tal vez tengas que ejecutar esta sencencia: *git config --global http.sslVerify false*

#### [ ¡AYÚDAME! ]

**PiKISS** crecerá de acuerdo a las peticiones de los usuarios o añadiré los scripts que considere oportunos, pero hago un llamamiento a **toda la comunidad** para compartir, mejorar o agregar nuevos scripts a los ya existentes. Que este proyecto crezca **depende de tí**.

¡Gracias!

José Cerrejón [(@ulysess10)](https://twitter.com/ulysess10)

Mail: <ulysess@gmail.com>

Blog: [https://misapuntesde.com](https://misapuntesde.com)

#### [ DONACIONES ]

Este proyecto ha supuesto muchas horas de pensar, buscar, refactorizar y testear código. Acepto donaciones por el esfuerzo que supone mantener y hacer nuevos scripts. Las donaciones no se requieren ni las espero. Cualquier cantidad que sientas que es apropiada sería de agradecer. Simplemente haz click en el botón "Donate" al final del documento. ¡Gracias! :)

<a href="https://www.paypal.com/cgi-bin/webscr?cmd=_donations&business=ulysess%40gmail%2ecom&lc=GB&item_name=PiKISS&currency_code=EUR&bn=PP%2dDonationsBF%3abtn_donate_SM%2egif%3aNonHosted"><img src="https://www.paypalobjects.com/en_GB/i/btn/btn_donate_SM.gif" /></a>
