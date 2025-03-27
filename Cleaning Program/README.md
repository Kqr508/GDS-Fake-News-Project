# Cleaning Program

Denne mappe er til ``Pre-Processing Program.py``, og de tilhørende filer og dokumentation.
Meningen med ``Pre-Processing Program.py``, er at den skal producere (og reproducere) en cleanet version af 995K datasættet, helt automatisk. Vær dog opmærksom på at denne kan tage noget tid, da det er krævende for computeren at arbejde med det store datasæt. Se progammet for yderligere info om dette.

Kravene for at køre programmet findes i ``requirements.txt``, og hvis dette ikke er installeret, risikeres at programmen ikke kan køre.
Desuden er programmet lavet til at køre med Python 3.12.
Dog gør programmet også brug af ``995,000_rows.csv`` datasættet, som derfor skal befinde sig i [Data mappen](https://github.com/Kqr508/GDS-Fake-News-Project/tree/main/Data). Denne fil kan downloades [her](https://absalon.ku.dk/courses/80486/files/9275000?wrap=1).

Desuden findes udviklings dokumentationen og processen i ``Text Cleaning development.ipynb``, som gør brug af viden fra Assignment 1.

## To the Examiner

To run the programs located in this folder, it is required that you meet the version and library requirements found in ``requirements.txt``.

The program to solve *Part 1, Task 1* is ``Text Cleaning development.ipynb``.  
To run the program correctly, you need to execute the cells in chronological order from the top, **except** for what comes after the heading *995K Pre-processing*.

The program to solve *Part 1, Task 2* is ``Pre-Processing Program.py``.  
To run the program correctly, it must be executed from the same directory in which it is located. This is something you need to pay special attention to if you are running it from VS Code.  
The program uses ``995,000_rows.csv``, which you should ensure is located in the ``Data`` folder. The file can be downloaded [here](https://absalon.ku.dk/courses/80486/files/9275000?wrap=1).  
Furthermore, when asked to choose a *"mode"*, you must select *Full* by pressing the key *F* and then pressing *Enter* twice.

*NOTE: Running this program may take some time.*

