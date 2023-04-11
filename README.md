# ML-for-Finance-Project

Im Ordner, in dem ihr das git repository lokal gespeichert habt, einmal in einem terminal den folgenden command ausführen:

`git config filter.strip-notebook-output.clean 'jupyter-nbconvert --ClearOutputPreprocessor.enabled=True --to=notebook --stdin --stdout --log-level=ERROR'`

Dadurch wird jedes mal bei einem commit der output aus dem jupyter notebook file entfernt, da es sonst immer conflicts gibt, wenn das jupyter notebook file ausgeführt wird.
