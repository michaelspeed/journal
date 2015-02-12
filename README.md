#Evolve Journal

##DISCLAIMER: This project is still in development and is subject to change.

Version: 0.5 (Beta)
____
###Dependencies

* gtk+-3.0
* libsoup-2.4
* json-glib-1.0
* gtksourceview-3.0

____
###To Build

Change to this folder (Journal's root folder)
   
>mkdir build
> 
>cd build
>
>cmake -DCMAKE_INSTALL_PREFIX=/usr ../
>
>make
>
>sudo make install

____
###Icons

* Journal icon copyright of Alejandro Seoane, many thanks!

To use the new icons, after having had Journal previously installed, run this command:
>sudo gtk-update-icon-cache /usr/share/icons/hicolor

###License

Journal is licensed under GPLv2