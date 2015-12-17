# CollegeFootball2015
Run the page rank algorithm based on 2015 football scores to evaluate the selection committee's rankings
Note: the scores were downloaded from here: http://www.sports-reference.com/cfb/years/2015-schedule.html

If you just want to generate the rankings...<br>
  1. download octave (or Matlab if you have it) - https://www.gnu.org/software/octave/download.html <br>
  2. execute at linux prompt: <b> linux> octave page.m </b><br>
  Output should look like this:<br>
  Clemson<br>
  Michigan State<br>
  Alabama<br>
  Stanford<br>
  Oklahoma<br>
  Houston<br>
  Iowa<br>
  Ohio State<br>
  ...

If you want to build the matrix from the scores or try it with data from a different season, do these additional steps...<br>
  1. download csv from a suitable website (such as http://www.sports-reference.com/cfb/years/2015-schedule.html)<br>
  2. run the football.py script with no arguments to generate the H matrix from stdout<br>
    <b> linux> ./football.py > H.mat </b>
  3. run the football.py script a second time with an argument to generate the file teams.csv<br>
    <b> linux> ./football.py 1 > teams.csv </b>
  4. run the page ranks in octave as above
    <b> linux> octave page.m </b><br> 
