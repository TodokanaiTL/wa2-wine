Check whether it's already enabled:

.. sourcecode:: sh

   locale -a | grep ja

If you see something like this, you can proceed to the next step.

.. sourcecode:: sh

   ja_JP
   ja_JP.eucjp
   ja_JP.ujis
   ja_JP.utf8
   japanese
   japanese.euc

.. MacOS

| Japanese locale should be enabled by default on Mac.
| You can check by running this command:

.. sourcecode:: sh

   locale -a | grep ja

Which should return something like this:

.. sourcecode:: sh

   ja_JP
   ja_JP.eucJP
   ja_JP.SJIS
   ja_JP.UTF-8

