Download Link: https://assignmentchef.com/product/solved-cs384-tutorial-5-cpi-spi-generator
<br>
You are given a <strong>grades.csv </strong>file that contains data for the grades for <strong>IIT Antartica</strong>. The content of the file are:

<strong>Roll</strong>: Roll of the student

<strong>Sem</strong>: Semester in which that sub is studied

<strong>SubCode</strong>: Course Code

<strong>Credit</strong>: Sub Credits

<strong>Grade</strong>: Obtained Grade

<strong>Sub Type</strong>: Whether Core or Elective etc <strong>names-roll.csv </strong>– This contains the mapping of names and roll numbers.

<strong>subjects </strong><strong>master.csv </strong>– This contains mapping of course codes and the name of the subject.

Your task is to generate a marksheet of every roll number and save as ”.xlsx” file in the output folder. A sample “0401CS02.xlsx” is provided for your reference. Its self explainable. The names of each sheet should be like the ones mentioned “0401CS02.xlsx”. Names: Overall, Sem1,…,SemN

Calculation of SPI and CPI: Suppose in a given semester a student has taken four courses having credits C1, C2, C3 and C4 and grade points in those courses are G1, G2, G3 and G4 respectively. Then,

<em>SPI </em>= (<em>C</em><sub>1 </sub>∗ <em>G</em><sub>1 </sub>+ <em>C</em><sub>2 </sub>∗ <em>G</em><sub>2 </sub>+ <em>C</em><sub>3 </sub>∗ <em>G</em><sub>3 </sub>+ <em>C</em><sub>4 </sub>∗ <em>G</em><sub>4</sub>)<em>/</em>(<em>C</em><sub>1 </sub>+ <em>C</em><sub>2 </sub>+ <em>C</em><sub>3 </sub>+ <em>C</em><sub>4</sub>)                                  (1)

<em>CPI </em>= (<em>SPI</em>1 ∗ <em>Credits in semester</em><sub>1 </sub>+ <em>SPI</em>2 ∗ <em>Credits in semester</em><sub>2 </sub>+ <em>…</em>)<em>/</em>(<em>Total credits</em>)                 (2)

For example, if in a given semester a student has taken four courses having credits 6, 6, 6, and 8 and grade points in those courses are 10, 9, 8, 6 respectively. Then,

<em>SPI </em>= (6 ∗ 10 + 6 ∗ 9 + 6 ∗ 8 + 6 ∗ 6)<em>/</em>(6 + 6 + 6 + 8) = 7<em>.</em>62                                   (3)

If the student has an SPI of 7.62 in the 1st semester worth (say) 32 credits and 8.2 in the next semester worth 36 credits,

<em>CPI</em>(<em>at the end of </em>2<em>nd semester</em>) = (7<em>.</em>62 ∗ 32 + 8<em>.</em>2 ∗ 36)<em>/</em>(32 + 36) = 7<em>.</em>93                      (4)

Grade Numeric Equivalent:

1

<ul>

 <li>AA – 10</li>

 <li>AB – 9</li>

 <li>BB – 8</li>

 <li>BC – 7</li>

 <li>CC – 6</li>

 <li>CD – 5</li>

 <li>DD – 4</li>

 <li>F – 0 I – 0</li>

</ul>

2