# Advanced Model

Denne mappe er tilegnet filer der relatere sig til [``Advanced Model development.ipynb``](https://github.com/Kqr508/GDS-Fake-News-Project/blob/main/Advanced%20Model/Advanced%20Model%20development.ipynb).
Dette program er lavet til at løse hele Part 3 i projektet. Programmet er også nødvendigt for at kunne lave evalueringen, da dette program træner og gemmer både den simple og den avancerede fake new detection model, til senere brug.

For at kunne køre dette program skal du opfylde versions og bibliotekts kravene fundet i [``requirements.txt``](https://github.com/Kqr508/GDS-Fake-News-Project/edit/main/Advanced%20Model/requirements.txt).
Derudover gør programmet brug af training og validation datasættene, som derfor skal befinde sig i [Data mappen](https://github.com/Kqr508/GDS-Fake-News-Project/tree/main/Data). Disse filer kan produceres med [``Pre-Processing Program.py``](https://github.com/Kqr508/GDS-Fake-News-Project/blob/main/Cleaning%20Program/Pre-Processing%20Program.py)

## To the Examiner

To run the programs located in this folder, it is required that you meet the version and library requirements found in ``requirements.txt``.

The program to solve *Part 3* (and *Part 2, Task 1*) is ``Advanced Model development.ipynb``.  
To run the program correctly, you need to execute the cells in chronological order from the top, **except** for what comes after the heading *Initial model experimentation*.

As the program makes use of the files ``Training_dataset.csv`` and ``Validation_dataset.csv``, it is necessary for these files to be located in the ``Data`` folder. If these files are not already in the folder, make sure to place it there before running the program. To produce these files, you must run the program ``Splitting Development.ipynb`` located in the ``Splitting Program`` folder.

To run the part where I test word embeddings, you will also need the following files:
- ``glove.6B.50d.txt``
- ``glove.6B.100d.txt``
- ``glove.6B.200d.txt``
- ``glove.6B.300d.txt``

Which need to be located in this folder (``Advanced Model``), and the files can be found in the ``glove.6B.zip`` file (which of course needs to be unzipped). The zip file can be downloaded from [*GloVe: Global Vectors for Word Representation*](https://nlp.stanford.edu/projects/glove/) website, or [here](https://nlp.stanford.edu/data/glove.6B.zip).

*NOTE: This program **will** run for a long time.*
