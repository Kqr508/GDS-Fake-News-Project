# Evaluation

Denne mappe er tilegnet filer der relatere sig til [``Evaluation.ipynb``](https://github.com/Kqr508/GDS-Fake-News-Project/blob/main/Evaluation/Evaluation.ipynb).
Denne notebook er lavet til at løse Part 4 i projektet, hvor den simple og avancerede model skulle testes på testing datasættet og LIAR datasættet.

For at kunne køre dette program, skal man opfylde versions og biblioteks kravene i [``requirements.txt``](https://github.com/Kqr508/GDS-Fake-News-Project/blob/main/Evaluation/requirements.txt).
Samt da programmet gør brug af testing sættet, skal denne befinde sig i [Data mappen](https://github.com/Kqr508/GDS-Fake-News-Project/tree/main/Data). Denne fil kan produceres med [``Pre-Processing Program.py``](https://github.com/Kqr508/GDS-Fake-News-Project/blob/main/Cleaning%20Program/Pre-Processing%20Program.py)
Derudover gør programmet brug af LIAR datasættet, man da dette er en lille datasæt befinder dette sig allerede i den korrekte mappe.

## To the Examiner

To run the programs located in this folder, it is required that you meet the version and library requirements found in ``requirements.txt``.

The program to solve *Part 4* is ``Evaluation.ipynb``.
As the program makes use of the file ``Testing_dataset.csv``, it is necessary for this file to be located in the ``Data`` folder. If this file is not already in the folder, make sure to place it there before running the program. To produce these files, you must run the program ``Splitting Development.ipynb`` located in the ``Splitting Program`` folder.

To run the program, you also need to make sure the following files exist in the *Advanced Model* folder:
- ``Advanced_model.pkl``
- ``Advanced_selector.pkl``
- ``Advanced_vectorizer.pkl``
- ``Simple_model.pkl``
- ``Simple_vectorizer.pkl``

To produce these files, you need to run the ``Advanced Model development.ipynb`` program in the ``Advanced Model`` folder.

To run the program correctly, you need to execute the cells in chronological order from the top.