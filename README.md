
(A) Recommended URLs:

1. Video courses:
   1.1 Arzu Ozoguz (UNC): Global Financial Markets and Instruments
       https://www.coursera.org/learn/global-financial-markets-instruments
   1.2 Damir Filipovic (EPFL): Interest Rate Models
       https://www.coursera.org/learn/interest-rate-models

2. A detailed syllabus with book titles:
   Global Association of Risk Professionals (GARP): Financial Risk Manager (FRM) 2020 Learning Objectives
   https://www.garp.org/#!/landing/2020-frm-learning-objectives


(B) How to use the jupyter notebooks on your computer:

1. Install anaconda on your computer<br/>
   . please see https://www.anaconda.com/products/individual

2. Download the files from this github repository to your computer<br/>
   . either download all files in a single zip package or git clone the repo

3. Open an anaconda prompt on your computer and install the conda environment<br/>
   . 3.1 change into the directory where you downloaded (or git cloned) the files<br/>
   . 3.2 `conda env create -f fin_course_env.yml`
 
4. Activate the installed conda environment with<br/>
   . `conda activate fin_course_env`

5. At the anaconda prompt set up nbextensions with<br/>
   . `jupyter contrib nbextension install --user`

6. Start using the notebooks in your default browser:<br/>
   . type `jupyter notebook` at your anaconda prompt

7. On the main page of jupyter notebook open the Nbextensions panel<br/>
   . 7.1 enable configurations: uncheck the "disable" box, if it is checked<br/>
   . 7.2 turn on the nbextension "Table of Contents"


