.. sourcecode:: sh

   export WINEARCH=win32
   export WINEPREFIX="$HOME/.local/share/wineprefixes/wa2"
   mkdir -p "$WINEPREFIX" && wineboot -u

Then, install the requirements:

.. sourcecode:: sh

   winetricks lucida corefonts cjkfonts # English & Japanese fonts
   winetricks devenum d3dx9 quartz # the DLLs required by the game
   winetricks wmp9 # includes the wmv codec used in the cutscenes

