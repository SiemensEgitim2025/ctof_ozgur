# Celsius-to-Fahrenheit Repository
A simple python script deployed as Flask App on Google App Engine with GitHub CI

How to run
        
        python -m pip install --upgrade pip
        
        pip install flake8 pytest
       
        if [ -f requirements.txt ]; then pip install -r requirements.txt; fi
  
Lint with flake8
       
        # stop the build if there are Python syntax errors or undefined names
     
        flake8 . --count --select=E9,F63,F7,F82 --show-source --statistics
      
        # exit-zero treats all errors as warnings. The GitHub editor is 127 chars wide
     
        flake8 . --count --exit-zero --max-complexity=10 --max-line-length=127 --statistics


Test with pytest

pytest -v


duzeltme1