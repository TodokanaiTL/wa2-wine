.. sourcecode:: sh

   mkdir -p "$HOME/.local/share/wineprefixes/wa2"
   export WINEARCH=win32 WINEPREFIX="$_" && wineboot

Then, install the requirements:

.. sourcecode:: sh

   winetricks fakejapanese_ipamona # Japanese fonts
   winetricks dxvk # DLL overrides required for subs

